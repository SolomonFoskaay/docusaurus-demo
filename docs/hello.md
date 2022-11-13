---
sidebar_label: 'Hello!'
sidebar_position: 3
---

# Hello

This is my **first Docusaurus document**!

Congratulations, you have made your first post!

Feel free to play around and edit this post as much you like.

# Title 1
Description

## Title 2
Description

### Title 2B
Description

## Title 3
Description

### Title 3B
Description

:::tip My tip

Use this awesome feature option

:::

:::danger Take care

This action is dangerous

:::

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