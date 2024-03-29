# Static website demo

Here is a simple demo to build a static website with GitHub Pages.

## How-to

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
