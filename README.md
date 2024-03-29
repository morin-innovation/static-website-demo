# Static website demo

Here is a simple demo to build a static website with GitHub Pages.

## Prepare DNS

To build a static website for your organization with custom domain name, you need to register domain into Pages settings of your organization:

`https://github.com/organizations/<organization-name>/settings/pages`

Then, you need to [redirect your DNS to GitHub](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).

In example, a A record for your destination domain with theses values (see official documentation for updated values):

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```
## Setup HTML code

As you can show in current repository, I just put `index.html` page and that's all. You can add all your assets here, like any static website.

## Setup GitHub Pages

Got to `https://github.com/<organization>/<repository>/settings/pages` (Repository Pages settings) to configure your domain and HTTPS.

Enjoy!

## Demo

Here is the static website from current repository:

https://static-website-demo.morin-innovation.com
