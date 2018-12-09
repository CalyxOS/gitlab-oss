# GitLab Ultimate or Gold for Open Source Projects

We take our responsibility of open source stewardship very seriously (https://about.gitlab.com/2016/01/11/being-a-good-open-source-steward/ and https://about.gitlab.com/stewardship/).

GitLab exists today in large part thanks to the work of hundreds of thousands of open source contributors around the world. To give back to this community who gives us so much, we want to help teams be more efficient, secure, and productive. We believe the best way for them to achieve this is by using as many of the capabilities of GitLab as possible.

It has already been the case for years that that any public project on GitLab.com gets all Gold features. We are happy to now offer a complimentary license to GitLab Ultimate (self-hosted) or subscription to GitLab Gold (SaaS) to all open source projects.

## Requirements

To apply:
- You need to be a project lead or a core contributor for an active open source project.
- Your project needs to use an [OSI-accepted open source license](https://opensource.org/licenses/alphabetical#)
- Your project **must not seek to make profit from the resulting project software**.

If you or your company work on commercial projects, consider our [plans for businesses](https://about.gitlab.com/pricing/).
If you're not sure if your project meets these requirements, please send an email to opensource@gitlab.com. 

We'll review all requests and accept them at our discretion. If accepted, your project will be listed below and we will send you a quote.

## How to apply

1.   Create a gitlab.com account for your open source project: https://gitlab.com/users/sign_in
1.   Create a fork of this project
1.   Edit the [`projects.yaml` file](data/projects.yaml) and add an entry for your project using this template:
     ```yaml
     -
     project_name: 'Project awesome'
     project_description: 'Describe what your project is about.'
     project_url: 'https://projectawesome.org (if you don't have a project site, use the GitLab project URL)'
     gitlab_plan: Gold or Ultimate
     ```
1.   Commit the changes to your fork and submit a new Merge Request against this project.
1.   Fill out the form at our [OSS page](https://about.gitlab.com/solutions/open-source/)

## License/subscription details

- You'll receive either a license for GitLab Ultimate or a subscription for GitLab Gold.
- Either of those will be valid for 1 year. After that period, a renewal will be required, which will be at no cost.
- Support is not included, but can be purchased for 95% off, at $4.95/user/month. [Contact Sales](https://about.gitlab.com/sales/) for that.
- Your license/subscription can be renewed each year for free if your project still meets the requirements.
   - [Contact Sales](https://about.gitlab.com/sales/) 30 days before your license/subscription ends.
- Licenses and subscriptions cannot be transferred or sold.
