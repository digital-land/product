---
name: "Digital land frontend"
status: "beta"
summary: "A python package used to generate the digital land pages. Includes templates, stylesheets and javascript modules."
---

A set of frontend assets that can be used to apply the digital land visual language to services and sites.

<div class="highlight-box--cta">
<p class="govuk-body">Digital land frontend is available on <a href="https://github.com/digital-land/frontend">github</a></p>
</div>

## Why we are building this

There are 2 main reasons to build our frontend product:

* consistency for our users
* convenience for digital land team

When we build prototypes, services and the digital land platform we want to maintain consistency. Consistency means our users will get a familiar experience irrespective of which service or part of the site they are on. A user can build up a mental model of how to interact with our site and services, for example, if a user sees a data record on our site they should know that any "identifer" fields will link through the associated data record.

Having components to reuse means common problems are solved once and then we move on to the next problem. The alternative is repeatedly solving the same problem.

It makes it easier to maintain the digital land platform and site. If we make a change to a component in the frontend then it will be applied to all parts of the site using the component.

## What we've done so far

Converted the [GOVUK frontend components](https://github.com/alphagov/govuk-frontend) to Jinja in [govuk-jinja-components](https://github.com/digital-land/govuk-jinja-components).

Created page templates to use for specific page types. For example, there is [a base template](https://github.com/digital-land/frontend/blob/main/digital_land_frontend/templates/dlf-base.html) and a template for [record pages](https://github.com/digital-land/frontend/blob/main/digital_land_frontend/templates/page-per-thing/record.html).

Created a number of components. These include a [data record component](https://github.com/digital-land/frontend/blob/main/digital_land_frontend/templates/components/data-record/macro.html) and a [filter group component](https://github.com/digital-land/frontend/blob/main/digital_land_frontend/templates/components/filter-group/macro.html). Examples of the components are on the [design system](https://digital-land.github.io/design-system/).

Created a [digital land stylesheet](https://github.com/digital-land/frontend/blob/main/digital_land_frontend/static/stylesheets/dl-frontend.css). This includes all the styles for the digital land components.

Create [DLFrontend.js](https://github.com/digital-land/frontend/blob/main/digital_land_frontend/static/javascripts/dl-frontend.js). This a javascript library with a number of modules used to progressively enhance our components.

Create [DLMaps.js](). A javascript library for our map related components.
