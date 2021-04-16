# 🧑‍💻Chapter Engineering Candidate Project

Congrats on making it to the project stage of Chapter's hiring process! With this project, we'd like to see how well you can build a modern, full stack application and test your ability to work with complicated data.

## The Basics

You're tasked with building a simple website that allows users to search Medicare plans.

Limit your work to around 4 hours.

Remember - you're building an MVP so prioritize functionality over performance. Focus on building a complete and functional web app.

## Getting Started

You're free to use whatever libraries, packages, of frameworks you like. We're less interested in which technologies you're familiar with and more with how you utilize them. Some popular ones that Chapter engineers like include:

- [Meteor.js](https://www.meteor.com/) with [React](https://guide.meteor.com/react.html)
- [Next.js](https://nextjs.org/)
- [Create React App](https://create-react-app.dev/)

## Important Terms

Health insurance is filled with dozens of confusing terms - here are a few that should help you out with this project.

- Bid ID: A unique identifier for Medicare Advantage plans. Of the following two forms:
  - `Hxxxx-xxx-xxx`, where all digits are required (e.g. "H1234-007-003")
  - `Hxxxx_xxx_y`, where the final "y" group has no trailing zeroes (e.g. "H1234_007_3")
- Insurance carrier: synonymous with "insurance company"
- Deductible: the amount of money the enrollee has to pay before the insurance carrier will pay anything
- Maximum out-of-pocket: The absolute maximum amount that the enrollee will have to pay in a given year

## Requirements

### Core Features
- Take as input a Bid ID (or partial Bid ID, e.g. `H0000-000`)
- Search the provided list of Medicare Advantage plans for the relevant entry(s)
- Display the following information:
  - Insurance carrier
  - Plan name
  - Geographic area served by this plan
  - The link to the plan's pharmacy website
  - The deductible amount
  - The max out-of-pocket amount

### Other requirements
- Functionality should be split into a front-end and back-end as appropriate
- A clear installation guide to help us run your project

## Data Files

We've included 2 data files and 1 data dictionary to base your work off of. We've intentionally left the files as they are exported from CMS, the government agency that consolidates Medicare data. As a result, you may find these files convoluted - that's okay! All files are TSVs.

- `pbp_Section_A.txt` - Contains basic information about Medicare plans.
- `pbp_Section_D.txt` - Contains more in-depth information about Medicare plans.
- `pbp_Benefits_2021_dictionary.txt` - A dictionary lookup for the column headers in the section A and section D files. Use this to make sense of the above two files.

If you get stuck, don't hesitate to reach out to darshan@getchapter.com or adam@getchapter.com with questions. Good luck!
