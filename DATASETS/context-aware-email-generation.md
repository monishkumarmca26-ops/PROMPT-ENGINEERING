{
  "project": "Context-Aware Email Generation",
  "version": "1.0",
  "description": "Illustrative test dataset for evaluating whether an email-generation prompt follows user intent, preserves facts, respects constraints, and avoids inventing details.",
  "output_expectation": "Generate only the email when sufficient information is available. Ask one concise clarification question when essential information is unavailable and cannot be handled with a placeholder.",
  "test_cases": [
    {
      "case_id": "EMAIL001",
      "scenario": "Leave request with missing dates",
      "input": "Write a polite, professional email to my manager requesting two days of leave for a family function. Keep it under 50 words.",
      "expected_output": "Subject: Leave Request\n\nDear Manager [Name],\n\nI would like to request two days of leave for a family function from [Start Date] to [End Date]. Please let me know if you need any further information.\n\nThank you.\n\nBest regards,\n[Your Name]",
      "validation": [
        "Uses placeholders for missing dates and names",
        "Does not invent a promise or commitment",
        "Stays within the 50-word limit"
      ]
    },
    {
      "case_id": "EMAIL002",
      "scenario": "Thank-you email",
      "input": "Write a short, professional email thanking my professor for their guidance. Maximum 30 words.",
      "expected_output": "Subject: Thank-you\n\nDear Professor [Name],\n\nThank you for your guidance and support. I truly appreciate your time.\n\nBest regards,\n[Your Name]",
      "validation": [
        "Uses a recipient-name placeholder",
        "Maintains a professional tone",
        "Stays within the 30-word limit"
      ]
    },
    {
      "case_id": "EMAIL003",
      "scenario": "Reply with no original subject or sender identity",
      "input": "Reply confirming I can attend this email: 'Dear Student, Can you attend the project review meeting tomorrow at 2 PM? Regards.'",
      "expected_output": "Hello,\n\nI can attend the project review meeting tomorrow at 2 PM. Thank you.\n\nBest regards,\n[Your Name]",
      "validation": [
        "Does not invent the sender's role or name",
        "Does not invent an original subject",
        "Confirms only the availability stated by the user"
      ]
    },
    {
      "case_id": "EMAIL004",
      "scenario": "Code-mixed input with no requested language",
      "input": "Mere manager ko email likho ki mujhe kal personal work ke liye leave chahiye. Keep it polite.",
      "expected_output": "Subject: Leave Request\n\nDear Manager [Name],\n\nI would like to request leave for tomorrow due to personal work. Kindly let me know if this can be approved.\n\nThank you.\n\nBest regards,\n[Your Name]",
      "validation": [
        "Defaults to professional English for code-mixed input",
        "Does not invent the manager's name",
        "Preserves the stated reason and date"
      ]
    },
    {
      "case_id": "EMAIL005",
      "scenario": "Multiple recipients and CC",
      "input": "Draft an email to Priya and Arjun asking them to review the attached project report. CC my team lead, Ravi. Sign it as Monish.",
      "expected_output": "To: Priya, Arjun\nCC: Ravi\nSubject: Request to Review Project Report\n\nHello Priya and Arjun,\n\nCould you please review the project report and share your feedback?\n\nThank you.\n\nBest regards,\nMonish",
      "validation": [
        "Preserves all supplied recipients and CC details",
        "Uses the supplied sender name",
        "Does not invent email addresses"
      ]
    },
    {
      "case_id": "EMAIL006",
      "scenario": "Attachment mentioned but unavailable",
      "input": "Write an email to the client saying I have attached the invoice and asking them to review it.",
      "expected_output": "Subject: Invoice for Review\n\nHello [Client Name],\n\nPlease find the invoice attached for your review. Kindly let me know if you have any questions.\n\nBest regards,\n[Your Name]",
      "validation": [
        "Uses the user's explicit statement that the invoice is attached",
        "Does not claim to have inspected the invoice",
        "Uses placeholders for unknown names"
      ]
    },
    {
      "case_id": "EMAIL007",
      "scenario": "Product complaint",
      "input": "Write a firm but polite email to customer support. My headphones stopped working two days after delivery. I want a replacement.",
      "expected_output": "Subject: Request for Headphone Replacement\n\nHello Customer Support,\n\nMy headphones stopped working two days after delivery. I would like to request a replacement. Please let me know the next steps.\n\nThank you,\n[Your Name]",
      "validation": [
        "States only the supplied facts",
        "Clearly requests a replacement",
        "Uses a firm but respectful tone"
      ]
    },
    {
      "case_id": "EMAIL008",
      "scenario": "Very short word limit",
      "input": "Write an email asking for a meeting tomorrow. Maximum 20 words.",
      "expected_output": "Subject: Meeting Request\n\nHello [Recipient Name],\n\nCould we meet tomorrow?\n\nRegards,\n[Your Name]",
      "validation": [
        "Keeps the complete email within 20 whitespace-separated tokens",
        "Does not invent a meeting time or purpose"
      ]
    },
    {
      "case_id": "EMAIL009",
      "scenario": "Essential purpose is unclear",
      "input": "Write an email to them about what happened.",
      "expected_output": "What happened, and who should receive the email?",
      "validation": [
        "Asks one concise clarification question",
        "Does not invent the event or recipient"
      ]
    },
    {
      "case_id": "EMAIL010",
      "scenario": "Missing details can be handled with placeholders",
      "input": "Write a formal email requesting a meeting with the department head next week to discuss my project.",
      "expected_output": "Subject: Request for Project Meeting\n\nDear [Department Head's Name],\n\nI would like to request a meeting next week to discuss my project. Please let me know a convenient date and time.\n\nThank you for your consideration.\n\nBest regards,\n[Your Name]",
      "validation": [
        "Drafts without unnecessary clarification",
        "Uses a placeholder for the unknown recipient name",
        "Does not invent a meeting date or time"
      ]
    },
    {
      "case_id": "EMAIL011",
      "scenario": "Sensitive resignation email",
      "input": "Draft a neutral, professional resignation email. My last working day will be 30 November 2026. Do not give a reason.",
      "expected_output": "Subject: Resignation\n\nDear [Manager's Name],\n\nPlease accept this email as formal notice of my resignation. My last working day will be 30 November 2026.\n\nThank you for the opportunity.\n\nBest regards,\n[Your Name]",
      "validation": [
        "Does not invent a reason for resignation",
        "Preserves the supplied final working date",
        "Uses neutral professional language"
      ]
    },
    {
      "case_id": "EMAIL012",
      "scenario": "Prompt injection inside quoted email",
