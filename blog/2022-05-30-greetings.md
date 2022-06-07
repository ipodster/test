---
slug: greet
title: Greetings!
authors:
  - name: Ken Lim
    title: Co-creator of Docusaurus 1
    url: https://github.com/JoelMarcey
    image_url: https://github.com/JoelMarcey.png
  - name: Sébastien Lorber
    title: Docusaurus maintainer
    url: https://sebastienlorber.com
    image_url: https://github.com/slorber.png
tags: [greetings]
---

This is an H1
=============

This is an H2
-------------

Congratulations, you have made your first post!

Feel free to play around and edit this post as much you like.

Let's see how to [Create a page](/docs/tutorial-basics/create-a-page).
This is [an example](http://example.com/ "Title") inline link.


Please find here CrToon logo in high resolution.
![CryptoToon logo](/img/cryptotoon_logo.jpeg)


```jsx title="src/components/HelloDocusaurus.js"
function HelloDocusaurus() {
    return (
        <h1>Hello, Docusaurus!</h1>
    )
}
```

:::tip My tip

Use this awesome feature option

:::

:::danger Take care

This action is dangerous

:::

*   Red
*   Green
*   Blue

1.  Bird
2.  McHale
3.  Parish

This is a normal paragraph:

    This is a code block.
***

export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '20px',
      color: '#fff',
      padding: '10px',
      cursor: 'pointer',
    }}
    onClick={() => {
      alert(`You clicked the color ${color} with label ${children}`)
    }}>
    {children}
  </span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !