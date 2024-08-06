# Issue Template Demo

This repository serves as a demonstration of how to use and configure issue templates on GitHub. Issue templates are a great way to guide contributors in submitting high-quality bug reports, feature requests, questions, and more.

## How to Submit an Issue

When submitting an issue in this repository, please follow the steps below to ensure your issue is clear and helpful:

1. **Navigate to the Issues tab**: Go to the [Issues](https://github.com/fjiangAI/issue_demo/issues) tab in this repository.

2. **Create a New Issue**: Click on the "New Issue" button.

3. **Choose an Issue Template**: Select the appropriate issue template from the list that best matches your needs. We offer the following templates:
   - **Bug Report**: For reporting bugs or issues in the project.
   - **Feature Request**: To suggest new features or improvements.
   - **Question**: For asking questions or requesting help.
   - **Documentation Improvement**: To suggest changes or additions to the documentation.
   - **Performance Issue**: For reporting performance-related issues.
   - **Security Issue**: To report security vulnerabilities (consider reporting privately).

4. **Fill Out the Template**: Provide all requested information in the template. This helps us understand and resolve your issue more effectively.

5. **Submit the Issue**: Once you have filled out the template, submit the issue for review.

## Best Practices for Submitting a Good Issue

Submitting a well-crafted issue is crucial for ensuring smooth project collaboration. A clear and detailed issue can help maintainers and contributors understand and resolve problems more quickly. Here are some best practices and guidelines for submitting good GitHub issues:

1. **Check for Duplicates**
   - Before submitting an issue, search existing issues in the project to ensure your problem or suggestion hasn't already been reported.

2. **Choose the Right Template**
   - Many projects offer issue templates, such as bug reports, feature requests, etc. Select the appropriate template when submitting an issue to help maintainers understand your problem better.

3. **Use a Concise Title**
   - Ensure the title is brief and accurately describes the core of the issue.
   - Avoid vague descriptions like "Help me" or "Problem here."

4. **Provide a Detailed Description**
   - Include complete information in your description:
     - **Problem Description**: Clearly state what the issue is.
     - **Steps to Reproduce**: Provide detailed steps to reproduce the problem so others can replicate it.
     - **Expected Outcome**: Describe what you expected to happen.
     - **Actual Outcome**: Describe what actually happened.

5. **Provide Environment Information**
   - Include relevant environment information such as operating system, browser version, and software version.
   - If the issue involves specific configurations or data, provide that information as well.

6. **Attach Screenshots or Logs**
   - If possible, attach screenshots that help illustrate the issue.
   - Provide relevant error logs or console output to aid in quick diagnosis.

7. **Suggest Solutions (if any)**
   - If you have suggestions or ideas on how to solve the problem, include them in the issue. This can spark discussion and may provide valuable insights.

8. **Be Polite and Respectful**
   - Use polite language and respect maintainers and contributors.
   - Avoid blaming or overly emotional language.

9. **Update and Follow Up**
   - If you find a solution or the issue progresses, update the issue accordingly.
   - Follow the issue's discussion and respond to questions from maintainers or other contributors.

## Setting Up Issue Templates

To set up issue templates in your own repository, follow these steps:

1. **Create the Templates Directory**: In your repository, create a `.github/ISSUE_TEMPLATE` directory.

2. **Add Template Files**: Add Markdown files for each type of issue template you want to support. Use descriptive names like `bug_report.md`, `feature_request.md`, etc.

3. **Configure Templates with `config.yml`**:
   - Create a `config.yml` file inside the `.github/ISSUE_TEMPLATE` directory.
   - Define your template configurations in this file to guide users through issue creation.


### Example `config.yml`

Here's an example configuration for `config.yml`:

```yaml
blank_issues_enabled: false
contact_links:
  - name: Bug Report (English)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=bug&template=01_en_bug_report.md&title=%5BBug%5D
    about: Report a bug in English to help us improve the project.

  - name: Bug Report (Chinese)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=bug&template=02_zh_bug_report.md&title=%5BBug%5D
    about: 提交一个中文的错误报告以帮助我们改进项目。

  - name: Feature Request (English)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=enhancement&template=03_en_feature_request.md&title=%5BFeature%5D
    about: Suggest a new feature in English for the project.

  - name: Feature Request (Chinese)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=enhancement&template=04_zh_feature_request.md&title=%5BFeature%5D
    about: 提出一个中文的功能请求来增强项目。

  - name: Question (English)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=question&template=05_en_question.md&title=%5BQuestion%5D
    about: Ask a question in English or request help regarding the project.

  - name: Question (Chinese)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=question&template=06_zh_question.md&title=%5BQuestion%5D
    about: 提出一个中文的问题或请求帮助。

  - name: Documentation Improvement (English)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=documentation&template=07_en_documentation_improvement.md&title=%5BDocs%5D
    about: Suggest an improvement to the documentation in English.

  - name: Documentation Improvement (Chinese)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=documentation&template=08_zh_documentation_improvement.md&title=%5BDocs%5D
    about: 提出中文的文档改进建议。

  - name: Performance Issue (English)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=performance&template=09_en_performance_issue.md&title=%5BPerformance%5D
    about: Report a performance issue in English related to the project.

  - name: Performance Issue (Chinese)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=performance&template=10_zh_performance_issue.md&title=%5BPerformance%5D
    about: 报告中文的性能问题。

  - name: Security Issue (English)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=security&template=11_en_security_issue.md&title=%5BSecurity%5D
    about: Report a security-related issue in English (consider reporting privately).

  - name: Security Issue (Chinese)
    url: https://github.com/your-username/your-repo/issues/new?assignees=&labels=security&template=12_zh_security_issue.md&title=%5BSecurity%5D
    about: 报告与安全相关的中文问题（建议私下报告）。
```

## Additional Tips

- Keep Templates Updated: Regularly review and update your templates to reflect changes in your project needs.

- Provide Clear Instructions: Ensure each template is clear and easy to follow.

- Engage with Contributors: Respond promptly to issues and provide guidance as needed.

By using issue templates, you can improve communication with contributors and streamline the issue management process in your project.


