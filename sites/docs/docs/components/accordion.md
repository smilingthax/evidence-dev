---
title: Accordion
sidebar_position: 30
---

<img src="/img/accordion.png" alt="accordion" width="600"/>

```markdown
<Accordion>
  <AccordionItem title="Item 1">
    This is the first item's accordion body.
  </AccordionItem>
  <AccordionItem title="Item 2">
    This is the second item's accordion body with <b>bold text</b>.
  </AccordionItem>
  <AccordionItem title="Item 3">
    This is the third item's accordion body.
  </AccordionItem>
</Accordion>
```

## Options

### `Accordion`

| Name   | Description                                                             | Required | 
|--------|-------------------------------------------------------------------------|----------|
| single  | When true, only a single accordian item can be open at once.           | No      | 


### `AccordionItem`

| Name   | Description                                                             | Required | 
|--------|-------------------------------------------------------------------------|----------|
| title  | The title of the accordion item. This will be displayed as the header   | Yes      | 
