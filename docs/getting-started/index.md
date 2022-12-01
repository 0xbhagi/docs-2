---
title: Getting Started
description: Getting Started is the place to get oriented and learn how to use Dune!
---

Getting Started is the place to get oriented and learn how to use Dune!

## Dune is made for technical and non-technical users alike.

Whether you are a seasoned SQL developer, blockchain researcher, business analyst or none of the above - you can use Dune to start analyzing Blockchain data in an instant.

With the help of our community, we've created a lot of helpful guides and tools to aid you in your journey of becoming a full-fledged Dune Wizard.

The absolute quickest way to get started with Dune is to follow along with our [Getting Started Video Series here](guides/video-tutorial.md) and to check out our [Getting Started Dashboard here](https://dune.com/dune/get-started).

The next steps to dive deeper depend on whether you:

1. Already know SQL
2. Are more of a just-in-case or just-in-time learner.

=== "Just-in-Case"
    Just-in-Case learning is school-style - read and watch a lot of content up front to get a general understanding, then start experimenting with doing.

    If this is your preferred learning style, our long form [Dune Guides](guides/dune-guides.md) go a lot deeper than our videos while still guiding you through simple projects to give you a general understanding of how to create with Dune.

    [OurNetwork Course](dune-guides/#ournetwork-course) is also provides a thorough, broad overview.

=== "Just-in-Time"
    Just-in-Time learning is for those who learn by doing. If you already have an idea of what you want to do with Dune and just need to unblock yourself by finding some specific tactical knowledge, [Core Features](queries/index.md) likely contains the information you need.

    [Tables](../reference/tables/index.md) and [Spellbook](../spellbook/index.md) are more advanced features worth experimenting with once you've understood the basics.

    Be sure to ask whatever questions you have in the [#beginners Discord channel](https://discord.com/channels/757637422384283659/1016725609797402634)!


=== "Don't Know SQL?"
    If you're not very familiar with SQL, start by exploring our [SQL Guides here](guides/sql-guides.md).


## What do you need to know to Become a Great Wizard?

![it's easy for Hermione](images/wingardium.gif)

### How to Use SQL

A fundamental understanding of SQL is needed to be able to successfully query for data on Dune.

[SQL](https://www.w3schools.com/sql/sql_intro.asp) is widely used in the Software Development industry and you can find a lot of non-Dune specific documentation about it. This often times helps with answering Query related questions since most answers can easily be found in the internet.


!!! note
    By default, this documentation shows information for our Dune V1 Engine, which runs on a PostgreSQL database.
    Our new data platform, [Dune Engine V2](https://dune.com/blog/dune-engine-v2) is currently in beta with a Spark SQL query engine. It offers exciting features like better scaling, cross chain Queries and [Spellbook](../spellbook/index.md). Dune Engine V2 will become the default over the next few months, so we recommend you try it out!

=== "Basic SQL"
    If you're not very familiar with SQL in general, we recommend starting with our [SQL Guides](guides/sql-guides.md).

=== "PostgreSQL"
    The official [PostgreSQL documentation](https://www.postgresql.org/docs/12/index.html) is great. Dune runs on PostgreSQL 12.2.

=== "Spark SQL"
    The official [Spark SQL](https://docs.databricks.com/sql/language-manual/index.html) documentation is super helpful.

### How to parse Ethereum Virtual Machine data

The data you will find on chain and in Dune's database is almost all pulled from Ethereum Virtual Machine based environments.

Thus, understanding how the Ethereum Virtual Machine and smart contracts work as a whole is an important foundation for being able to find, understand, and use much of the data available in Dune.

If you are able to read most of the data in Etherscan, you're already well on your way to being able to create insightful Queries and Visualizations with Dune.

Unfortunately we haven't yet found one great resource we can point you to currently as each smart contract has it's own rules. We have written up a few words on this in our section on [Decoded Data](../reference/tables/decoded/index.md).

### What communities, protocols, and businesses care about

This is something that might come as a surprise to you but a key component of being an effective data-analyzing Wizard is understanding how to separate "signal from noise."

Some data is interesting and valuable, some data isn't. Knowing how to surface the interesting bits by making them clear and easy to understand is a fundamental part of becoming a great data-analyzing Wizard.

Ask yourself: 

!!! quote "What Data is interesting and needed for my audience/community/project/company to make better decisions?"

There are thousands of ways to go about finding metrics that are interesting, though talking with the community or founders is usually the best starting place.

## How to find a freelancer to help you build Dune Dashboards

There are quite a few people in the crypto industry who either specialize in building on Dune or have the necessary skills to quickly get up to speed on the particulars.

To reach out to this pool of freelancers, you can [**fill out this questionnaire**](http://bounties.dune.com) and hopefully freelancers will get back to you in little to no time. If that yields no results, posting the bounty on relevant social channels and spreading it in your networks may help.

If hiring a freelancer for the first time, please be sure to review their past work and Dashboards to verify that they are indeed capable of the kind of problem solving you need.

## Additional Tools and Support

Check out our [Support](../reference/support-feedback.md) page to learn the best way to get help if you can't find the answers you're looking for in our docs.

And give our [Wizard Tools](../reference/wizard-tools/index.md) page a gander to learn more about all the awesome non-Dune tools our wizards use to make 🎇.