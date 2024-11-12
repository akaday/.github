# akaday/.github

## Project Description

This repository provides GitHub workflows and templates for managing pull requests and other repository-related tasks.

## Purpose of the Repository

The purpose of the `akaday/.github` repository is to provide GitHub workflows and templates for managing pull requests and other repository-related tasks.

* The repository contains workflows, such as the `auto-close-pr` workflow, which automatically closes pull requests from non-staff members. This workflow is defined in `.github/workflows/auto-close-pr.yml` and `workflow-templates/auto-close-pr.yml`.
* The repository also includes a `profile/README.md` file that provides information and resources for the GitHub Community, including guidelines, documentation, and ways to participate.
* The `workflow-templates/auto-close-pr.properties.json` file provides metadata for the `auto-close-pr` workflow, including its name and description.

## Instructions on How to Use the Workflows

1. Ensure that the necessary secrets are configured in your repository settings.
2. Add the workflow files to the appropriate directories in your repository.
3. Customize the workflow files as needed to suit your repository's requirements.
4. Commit and push the changes to your repository.

## Explanation of the `auto-close-pr` Workflow

The `auto-close-pr` workflow automatically closes pull requests from non-staff members. It is defined in the `.github/workflows/auto-close-pr.yml` and `workflow-templates/auto-close-pr.yml` files. The workflow checks if the pull request author is a member of the organization. If the author is not a member, the workflow closes the pull request and leaves a comment explaining the reason.

## Additional Resources and Information

For additional resources and information, please refer to the [profile/README.md](profile/README.md) file.

## Contribution Guidelines

We do not accept external contributions to this repository.

## Contact Information

For support or inquiries, please contact the repository maintainers.
