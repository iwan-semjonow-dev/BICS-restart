# BICS — Financial Energy System

BICS is a beginner-friendly portfolio project for a one-page web application that analyzes personal spending through a behavioral model.

The goal of BICS is not only to show where money goes, but also to help understand why a purchase was made.

## BICS Model

BICS uses four behavioral spending categories:

* **Basic** — necessary basic expenses.
  Example: apartment rent.

* **Invest** — development, education, health, useful tools, and assets.
  Example: a JavaScript course.

* **Chaos** — impulsive and unplanned spending.
  Example: spontaneous food delivery.

* **Signal** — status, image, and self-presentation spending.
  Example: an expensive watch.

## Core Idea

In BICS, the important part is not only the purchase itself, but also the reason behind the purchase.

For example, sneakers can belong to different categories:

* **Basic**, if the old pair is worn out and needs to be replaced;
* **Signal**, if the purchase is made for image or status;
* **Chaos**, if the purchase is a spontaneous impulse.

The same object can have a different behavioral meaning depending on the reason behind it.

## First MVP

The first version of the project includes:

* a header;
* a short explanation of the BICS model;
* four BICS categories;
* a list of example transactions.

## Current Status

The project has moved from the first HTML/CSS stage into JavaScript console-first learning.

Current JavaScript work focuses on:

* transaction data;
* arrays and objects;
* reading object properties;
* loops;
* conditions;
* functions;
* totals;
* percentages;
* stats objects;
* console-based analytics logic.

The current calculations are practiced in `script.js`, but they are not rendered to the DOM yet.

## Not Included Yet

The project does not include these features yet:

* transaction creation form;
* user input;
* DOM rendering;
* localStorage;
* dashboard UI;
* charts;
* goals and savings;
* recurring expenses;
* backend;
* database;
* authentication.

These features may be added later, after the JavaScript foundations are stronger.

## Future Product Vision

In the future, BICS can grow into a dashboard-style web application for understanding personal financial energy and spending behavior.

The mockup in `assets/mockups/bics-future-dashboard.jpg` shows the long-term visual direction of the product. It is a visual reference, not the current development task.

The future dashboard may include:

* header with the BICS title and subtitle;
* date range selector;
* period selector;
* summary cards for balance, income, expenses, investments, and financial energy;
* main BICS circle with the four behavioral categories: `Basic`, `Invest`, `Chaos`, and `Signal`;
* financial energy score;
* expense structure with regular spending categories, percentages, and amounts;
* transactions list;
* recurring expenses;
* goals and savings;
* quick add form;
* charts;
* filters;
* reports.

## Important Distinction

BICS categories describe the behavioral reason behind spending:

* `Basic`
* `Invest`
* `Chaos`
* `Signal`

Expense categories describe the practical type of spending, such as:

* food;
* transport;
* subscriptions;
* health;
* rent;
* education;
* accessories.

A BICS category answers the question: **why was the money spent?**

An expense category answers the question: **what type of expense was it?**

## Development Approach

Current development happens through small learning steps.

The project is built with:

* HTML;
* CSS;
* JavaScript.

The focus is on learning and understanding the code, not on generating a full application as fast as possible.

The full dashboard should not be built until the JavaScript foundations are ready.
