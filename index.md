---
layout: page
title: Stéphane Tailland @ Software AG
description: Collection of useful information items and links
---

Find here some useful information items and links regarding Software AG and its products.
This page focuses on products related APIs, Applicative Integration and Microservices.

### Integration microservices

Over the last few years, webMethods has undergone a transformation to become an integration microservice platform.  
You still get the power of the good old webMethods ESB platform: connectivity to virtually anything, standardized low-code integrations, high performance, just to name a few.

But you can now implement and deploy your integration in lightweight containers, and you can do it according to the DevOps practices.

You get a platform that can easily expose synchronous and asynchronous APIs.

The lightweight container version of the webMethods ESB is called Microservice Runtime (or MSR.)

The MSR is available in [Docker Hub](https://hub.docker.com/r/softwareag/webmethods-microservicesruntime), it embeds a trial license of 90 days.

You can also download a [full IDE in the Tech Forum.](https://tech.forums.softwareag.com/t/webmethods-service-designer-download/235227)

With the MSR you still implement your integrations using the Service Designer and you do it with a local instance of the MSR.

You manage your generated code in Git, with feature branching and pull requests (if you want.)

You then build a Docker image and push it to a container registry.

You can deploy the resulting image in a simple Docker host, in Container as a Service platforms or in Kubernetes (or OpenShift.)

You can use the traditional automated test tools (like Postman / Newman.)

And of course you can orchestrate all these activities using the CI/CD tool of your choice (Jenkins, Github actions, Azure Pipelines, ...)

Useful links:
-   [Customer Management microservice showcase](https://github.com/staillansag/msr-customer-management-v2)
-   [Building an integration microservice from A to Z with webMethods and Kubernetes](https://tech.forums.softwareag.com/t/building-an-integration-microservice-from-a-to-z-with-webmethods-and-kubernetes/267171/1)
-   [webMethods Product Deep Dive: Microservices Runtime and Containers IUG 2022](https://tech.forums.softwareag.com/t/webmethods-product-deep-dive-microservices-runtime-and-containers-iug-2022/267502)

### Serverless and hybrid integrations


### API Management




[Github Pages](https://pages.github.com) provide a simple way to make a
website using
[Markdown](https://daringfireball.net/projects/markdown/) and
[git](https://git-scm.com).

For me, the painful aspects of making a website are

- Working with html and css
- Finding a hosting site
- Transferring stuff to the hosting site

With [GitHub Pages](https://pages.github.com), you just write things in
[Markdown](https://daringfireball.net/projects/markdown/),
[GitHub](https://github.com) hosts the site for you, and you just push
material to your GitHub repository with `git add`, `git commit`, and
`git push`.

If you love [git](https://git-scm.com/) and
[GitHub](https://github.com), you'll love
[GitHub Pages](https://pages.github.com), too.

The sites use [Jekyll](https://jekyllrb.com/), a
[ruby](https://www.ruby-lang.org/en/) [gem](https://rubygems.org/), to
convert Markdown files to html, and this part is done
automatically when you push the materials to the `gh-pages` branch
of a GitHub repository.

The [GitHub](https://pages.github.com) and
[Jekyll](https://jekyllrb.com) documentation is great, but I thought it
would be useful to have a minimal tutorial, for those who just want to
get going immediately with a simple site. To some readers, what GitHub
has might be simpler and more direct.  But if you just want to create
a site like the one you're looking at now, read on.

Start by reading the [Overview page](pages/overview.html), which
explains the basic structure of these sites. Then read
[how to make an independent website](pages/independent_site.html). Then
read any of the other things, such as
[how to test your site locally](pages/local_test.html).

- [Overview](pages/overview.html)
- [Making an independent website](pages/independent_site.html)
- [Making a personal site](pages/user_site.html)
- [Making a site for a project](pages/project_site.html)
- [Making a jekyll-free site](pages/nojekyll.html)
- [Testing your site locally](pages/local_test.html)
- [Resources](pages/resources.html)

If anything here is confusing (or _wrong_!), or if I've missed
important details, please
[submit an issue](https://github.com/kbroman/simple_site/issues), or (even
better) fork [the GitHub repository for this website](https://github.com/kbroman/simple_site),
make modifications, and submit a pull request.

---

The source for this minimal tutorial is [on github](https://github.com/kbroman/simple_site).

Also see my [tutorials](https://kbroman.org/tutorials) on
[git/github](https://kbroman.org/github_tutorial),
[GNU make](https://kbroman.org/minimal_make),
[knitr](https://kbroman.org/knitr_knutshell),
[R packages](https://kbroman.org/pkg_primer),
[data organization](https://kbroman.org/dataorg),
and [reproducible research](https://kbroman.org/steps2rr).
