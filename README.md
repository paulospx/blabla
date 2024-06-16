# blabla
Ever been caught red-handed with a "blabla" reason for a role permission request? Fear not! 

The **blabla** is here to save the day (and your productivity). No more awkward explanations or creative dry spells—our handy tool generates plausible reasons for requesting role permissions. Perfect for baffling your colleagues and impressing your role approvers with the perfect reason.

## Features

- Generates a random, plausible reason for role permission requests.
- Customizable reason templates to suit your wildest whims.
- Easy to use and guaranteed to bring your request to you.

## Installation

You can use this project as a browser *bookmarklet*.

## Usage

Create a bookmarklet with the following link:

```javascript
javascript:(function(){var d=document,s=d.createElement('script');s.src='https://paulospx.github.io/blabla/blabla.js';d.body.appendChild(s);}())
```

### Customizing Reason Templates

Feel like getting even more creative? You can customize the templates used for generating reasons by editing the `templates.json` file. This file contains a list of templates with placeholders that can be filled with random values.

Example `templates.json`:

```javascript
  var reasons_list = [
    'Job Responsibilities: Access is necessary to perform regular job duties and responsibilities.', 
    'Project Collaboration: Access is needed for collaboration on a specific project.', 
    'Training and Skill Development: Access is required for training and skill development purposes.', 
    'Data Analysis: Access is necessary for analyzing data to make informed decisions.', 
    'Report Generation: Access is essential for generating reports and presenting findings.', 
    'Compliance and Auditing: Access is needed for compliance and auditing purposes.', 
    'Troubleshooting: Access is required to troubleshoot issues and provide technical support.', 
    'Testing and Quality Assurance: Access is necessary for testing software or systems and ensuring quality.', 
    'Security Investigations: Access is needed to investigate security incidents or potential threats.', 
    'Process Improvement: Access is required to identify areas for process improvement.', 
    'Emergency Response: Access is necessary for responding to emergencies or critical situations.', 
    'Strategic Planning: Access is needed for strategic planning and decision-making.', 
    'Customer Support: Access is essential for providing effective customer support.', 
    'Vendor Management: Access is required for managing relationships with external vendors.', 
    'Policy Implementation: Access is necessary for implementing and enforcing company policies.', 
    'Regulatory Compliance: Access is needed to ensure compliance with industry regulations.', 
    'Innovation and Research: Access is essential for innovation and conducting research.', 
    'System Integration: Access is required for integrating systems and ensuring smooth operations.', 
    'Backup and Recovery: Access is needed for managing backup and recovery processes.', 
    'User Access Management: Access is necessary for managing user roles and permissions within the system.'
  ];
```



## Contributing

Got a hilarious idea for a new template? We welcome contributions! If you have suggestions for new features, templates, or bug fixes, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions, suggestions, or just to share a laugh, please open an issue.

