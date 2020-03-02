---
layout: hosting_providers
title: Does My Hosting Provider Offer HTTPS?
class: hosting
---

## How did you set up your website?

If you have a website, you maybe went through a process that included:
<ol>
  <li>
    Buying a {% include tooltip.html term-name="domain-name" text="domain" %} from a company (yourwebsite.com)
  </li>
  <li>
    Choosing a {% include tooltip.html term-name="server" text="server" %} to host that website. This often involves picking a {% include tooltip.html term-name="hosting-provider" text="hosting provider" %}.
    {% include hosting_provider_graphic.html %}
  </li>
  <li>
    Often, people will pick a {% include tooltip.html term-name="shared-hosting" text="shared hosting product" %} from the hosting provider, which may include an HTTPS certificate as part of their package. This page is for these users.
  </li>
</ol>

## Do you use shared hosting?

If you’re not using the shared hosting product, or if your provider doesn’t appear here, check out our [instructions](/instructions) for using Certbot or [get help](/help).

**_The list is categorized into:_**

<p class="the-list"><a id="all-bounce" href="#table-anchor">All Hosting providers</a>: Find your provider here.</p>

<p class="the-list"><a id="full-bounce" href="#table-anchor"><img alt="Full HTTPS support" src="/images/GreenCheck.svg">Full HTTPS Support</a>: Hosting providers that offer free Let’s Encrypt HTTPS certificates automatically for their shared hosting product. No need to do anything on your end if you use their service.</p>

<p class="the-list"><a id="partial-bounce" href="#table-anchor"><img alt="Partial HTTPS support" src="/images/PartialHTTPSSupport.svg">Partial HTTPS Support</a>: Hosting providers that offer free Let’s Encrypt HTTPS certificates for their shared hosting product, but require configuration. You’ll need to follow a tutorial.</p>

<p class="the-list"><a id="no-bounce" href="#table-anchor"><img alt="No HTTPS support" src="/images/NoHTTPSSupport.svg">No HTTPS Support</a>: Hosting providers that do not offer free HTTPS certificates for their shared hosting product. It may or may not be possible to use Certbot with other products that the provider offers, such as their VPS product.</p>
