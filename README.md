# Engineering Practicum

We are an very practical team at Microsoft and this extends to the way that we work with you to find out if this team is a great fit for you. We want you to come away with a great understanding of the work that we actually do day to day and what it is like to work with us.

Instead of coding at a whiteboard with someone watching over your shoulder under high pressure, which is not a thing we often do, we instead give out an engineering assignment for you to work on before we meet in person. We'll then continue to work with you on the assignment on site.

## Guidelines

-   Our team builds, alongside our customers, systems engineered to run in production. Given this, please organize, design, test, document, and deploy this code as if it were going into production.

*   Our team meets our customers where they are in terms of software engineering platforms, frameworks, and languages. This means you have wide latitude to make choices that express the best solution to the problem.

*   This is meant to be an assignment that you spend approximately three hours of dedicated, focused work. Do not feel like you need to overengineer the solution with dozens of hours to impress us. Be biased toward quality over quantity.

*   Think of this like an open source project. Create a repo on Github, use git for source control, and use README.md to document what you built for the newcomer to your project.

*   Think out loud in your submission's documentation. Document tradeoffs, the rationale behind your technical choices, or things you would do or do differently if you were able to spend more time on the project or do it again.

## The Problem

Our San Francisco team loves to eat. Being a team that loves variety, be it in the variety of technologies we use in our customer projects -- or food -- so we also like to discover new places to eat.

In fact, we have a particular affliction for food trucks. In this problem, we would like you to make it easier for us to find nearby food trucks.

One of the great things about Food Trucks in San Francisco, is that the city releases a list of them as open data.

Your assignment is to make it possible for us to find a food truck no matter where our work takes us in the city.

This is a freeform assignment. You can write a web API that returns a set of food trucks (our team is fluent in JSON). You can write a web frontend that visualizes the nearby food trucks. We also spent a lot of time in our shells, so a CLI that gives us a couple of local options would be just as great.

The only requirement for the assignment is that it give us at least 5 food trucks close to this latitude and longitude.

Feel free to tackle this problem in a way that demonstrates your expertise of an area or takes you out of your comfort zone. For example, if you build Web APIs by day and want to build a frontend approach to the problem or a completely different language instead, by all means go for it - learning is a core competency in our group. Let us know this in your solution's documentation.

San Francisco's food truck open dataset is [located here](https://data.sfgov.org/Economy-and-Community/Mobile-Food-Facility-Permit/rqzj-sfat/data) and there is an endpoint with a [CSV dump of the latest data here](https://data.sfgov.org/api/views/rqzj-sfat/rows.csv). We've included a [copy of this data](./Mobile_Food_Facility_Permit.csv) in this repo as well.

Good luck!
