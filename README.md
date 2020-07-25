# Legal Consultation App

[![GitHub contributors](https://img.shields.io/github/contributors/code4romania/legal-consultation-client.svg)](https://github.com/code4romania/legal-consultation-client/graphs/contributors) [![GitHub last commit](https://img.shields.io/github/last-commit/code4romania/legal-consultation-client.svg)](https://github.com/code4romania/legal-consultation-client/commits/master) [![License: MPL 2.0](https://img.shields.io/badge/license-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0)  ![](https://github.com/code4romania/expert-consultation-client/workflows/Build/badge.svg)

Webapp client for Legal Consultation, a project designed to ease the process of public consultation with experts in Romania.

[See the project UX](https://www.figma.com/proto/7VLlmWKJOjS3YXkOFjMRi0/Legal-Consultation?node-id=0%3A1&scaling=min-zoom) and [the preview environment](https://expert-consultation-client.now.sh) with the work in progress.

Whenever a group or institution proposes a new law, there is a time when they need to consult with expert communities. For example, legislation on urban planning, construction, or architecture generally reaches the Architects' Order in Romania for consultation. The consultation period is very short and most of the time, not all members of these expert groups have the necessary time and tools to make their contribution effective. The consultation process within the group is very ad-hoc, made through physical documents, social media, or excel files forwarded back and forth between all participants, and these groups sometimes have more than 4-5 thousand experts who should get information and come back in a few days.

At the end of the consultation, things become even more complicated because a person needs to validate and consolidate all feedback in a coherent form that can be sent back to the ministry.

We build a digital tool for this type of consultation to allow these groups to work directly on the text, to contribute feedback, suggestions, comments, vote and amend certain proposals, articles or comments from other participants etc. and then automatically reinforce the final document. This tool will make it easier to consult with experts, giving enough time for everyone to express their opinion, eliminating unnecessary bureaucracy and allowing real-time access to the same information for thousands of people who otherwise would only interact with a single point of contact - centralizes everyone's opinions. At the same time, it eliminates all the useless time spent on formatting the law, consolidating similar comments, eliminating unnecessary or irrelevant comments, etc.

A big problem is also the legislative hat and the fact that when feedback is needed, they need to have access to a suite of other legislative documents in order to give a pertinent comment, which so far falls under the responsibility of each of them and has the capacity everyone to discern which adjacent document is relevant or not. Digital tools allow them to consult other relevant laws directly on the platform and make the necessary connections for all participants on their own.

The tool also contributes to the transparency of the consultation process, which will now be open to everyone, where everyone can see the comments of others and the end product.

To find out more about this project, [check it out on Civic Labs](https://civiclabs.ro/ro/solutions/expert-consultation), the Code for Romania research and prototyping program.

[Contributing](#contributing) | [Built with](#built-with) | [Repos and projects](#repos-and-projects) | [Deployment](#deployment) | [Feedback](#feedback) | [License](#license) | [About Code4Ro](#about-code4ro)

## Contributing

This project is built by amazing volunteers and you can be one of them! Here's a list of ways in [which you can contribute to this project](.github/CONTRIBUTING.md). If you want to make any change to this repository, please **make a fork first**.

Help us out by testing this project in the [staging environment](https://expert-consultation-client.now.sh/home). If you see something that doesn't quite work the way you expect it to, open an Issue. Make sure to describe what you _expect to happen_ and _what is actually happening_ in detail.

If you would like to suggest new functionality, open an Issue and mark it as a __[Feature request]__. Please be specific about why you think this functionality will be of use. If you can, please include some visual description of what you would like the UI to look like, if you are suggesting new UI elements. 

Also, this is [the workflow we follow](.github/WORKFLOW.md). 

## Built With

### Programming languages

JavaScript

### Platforms

### Frontend framework

Angular

### Package managers

npm

### Database technology & provider

## Repos and projects

- [Legal Consultation API](https://github.com/code4romania/legal-consultation-api)

## Deployment

- npm install
- npm start

### [With docker-compose](etc/docker/README.md)

Your server will start on `localhost:4200`

## Feedback

* Request a new feature on GitHub.
* Vote for popular feature requests.
* File a bug in GitHub Issues.
* Email us with other feedback contact@code4.ro

## License

This project is licensed under the MPL 2.0 License - see the [LICENSE](LICENSE) file for details

## About Code4Ro

Started in 2016, Code for Romania is a civic tech NGO, official member of the Code for All network. We have a community of over 500 volunteers (developers, ux/ui, communications, data scientists, graphic designers, devops, it security and more) who work pro-bono for developing digital solutions to solve social problems. #techforsocialgood. If you want to learn more details about our projects [visit our site](https://www.code4.ro/en/) or if you want to talk to one of our staff members, please e-mail us at contact@code4.ro.

Last, but not least, we rely on donations to ensure the infrastructure, logistics and management of our community that is widely spread across 11 timezones, coding for social change to make Romania and the world a better place. If you want to support us, [you can do it here](https://code4.ro/en/donate/).
