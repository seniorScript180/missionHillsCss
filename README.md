# CTA css classes

## How to use:

base class: cta

state class: \[**cta-solid-on** OR **cta-outline-on**\]  -  \[**dark** OR **light** OR **primary**\]

example:

```html
<a class="cta cta-solid-on-dark" href="">Primary CTA</a>
<a class="cta cta-outline-on-dark" href="">Secondary CTA</a>

<a class="cta cta-solid-on-primary" href="">Primary CTA</a>
<a class="cta cta-outline-on-primary" href="">Secondary CTA</a>

<a class="cta cta-solid-on-light" href="">Primary CTA</a>
<a class="cta cta-outline-on-light" href="">Secondary CTA</a>
```

Primary can be a color with any HUE value \[0-355\]

The Outline on Primary doesn't really work on HUE values \[211-300\]
on hover state.