# Typography Fundamentals

Typography is one of the most important foundations of UI design.

Before choosing colors, creating layouts, or designing components, designers must understand how to present text effectively.

Typography is not only about making text look good. In UI design, typography is a system used to organize information, guide attention, and reduce the effort required to understand content.

A strong typography system is built around:

* Readability
* Visual hierarchy
* Consistency
* Accessibility

---

# What You'll Learn

In this lesson, you'll learn:

* What typography is and why it matters
* How to choose appropriate fonts
* Typography scales
* Font sizes
* Font weights
* Line height
* Letter spacing
* Visual hierarchy
* Common typography mistakes
* Accessibility considerations
* How to apply typography decisions in real interfaces

---

# What is Typography?

Typography is the practice of arranging text to make it readable, understandable, and visually appealing.

In UI design, typography includes:

* Typeface selection
* Font size
* Font weight
* Line height
* Letter spacing
* Text alignment
* Visual hierarchy

These elements work together to determine how users consume information within an interface.

---

# Why Typography Matters

Typography directly impacts user experience.

Good typography helps users:

* Read content comfortably
* Scan information faster
* Understand content structure
* Focus on important information
* Navigate interfaces with less effort

Poor typography can lead to:

* Reduced readability
* Visual clutter
* Confusing layouts
* Increased cognitive load

The goal of typography is not decoration.

The goal is communication.

---

# Choosing a Font

The first typography decision is selecting a typeface.

For digital products, sans-serif fonts are commonly used because they are clean, modern, and readable on screens.

---

## Popular UI Fonts

| Font                     | Common Usage                               |
| :------------------------- | :------------------------------------------- |
| **Inter**          | Modern web applications                    |
| **SF Pro Display** | Apple ecosystem (iOS/macOS)                |
| **Roboto**         | Android applications & Google products     |
| **Open Sans**      | Content-heavy websites & dashboards        |
| **Poppins**        | Modern, geometric, and creative interfaces |

---

## Font Selection Guidelines

Choose fonts that:

* Are easy to read
* Support required languages
* Match the product personality
* Work well across different devices

Avoid using many font families because it reduces consistency.

A common rule:

> One primary font family is enough for most products.

---

# Typography as a System

Professional interfaces do not choose font sizes randomly.

Instead, designers create a typography system where every text style has a clear purpose.

Example:

* Large text → communicates importance
* Medium text → creates structure
* Small text → supports additional information

The purpose is to create predictable patterns users can understand.

---

# Typography Scale

A typography scale is a predefined set of text sizes used consistently throughout a product.

Instead of choosing random, guessing values:

```text
H1 = 37px
H2 = 26px
```

Professional designers use calculated mathematical relationships to create balanced and predictable systems.

---

## Using Ratios

A highly effective method is establishing a scale ratio to generate balanced step-sizes.

> **The Scale Formula:**
> 
> **Next Size = Current Size × Scale Ratio**

---

### Example Using a 1.25 Ratio (Major Third)

**Base (Body):**

```text
16px
```

**Step 1 (H3):**

```text
16px × 1.25 = 20px
```

**Step 2 (H2):**

```text
20px × 1.25 = 25px
```

**Step 3 (H1):**

```text
25px × 1.25 = 31.25px
```

Rounded:

```text
31px → 32px
```

This mathematical progression creates a natural visual rhythm and makes layout decisions more consistent.

---

# Font Sizes

Font size helps establish importance and hierarchy.

## Common UI Sizes

| Element           | Default Size | Role in Hierarchy                 |
| :------------------ | :------------- | :---------------------------------- |
| **H1**      | 40px         | Primary Page Title                |
| **H2**      | 32px         | Major Section Heading             |
| **H3**      | 24px         | Sub-section Title / Card Header   |
| **Body**    | 16px         | Standard Paragraph Text (Default) |
| **Caption** | 14px         | Secondary Meta-data / Timestamps  |

---

## Why 16px for Body Text?

16px is commonly used because:

* It is comfortable for reading
* It works well across different screen sizes
* It reduces the need for zooming

Smaller sizes are usually reserved for secondary information.

Example:

```text
Body:
16px

Caption:
14px
```

---

# Font Weight

Font weight controls how thick or thin text appears.

## Common Weights

| Weight        | Name      | Common UI Usage                             |
| :-------------- | :---------- | :-------------------------------------------- |
| **400** | Regular   | Body copy, paragraphs, and long text blocks |
| **500** | Medium    | Navigation links, secondary buttons         |
| **600** | Semi-Bold | Component titles, card headers              |
| **700** | Bold      | Primary page titles, prominent alerts       |

Font weight creates importance without always increasing size.

---

# Line Height

Line height controls the vertical space between lines.

The correct value depends on the type of text.

A common mistake is using the same line height for headings and paragraphs.

---

## Body Text Line Height

Paragraphs need more space because users read multiple lines continuously.

Formula:

```text
Line Height = Font Size × 1.4 – 1.6
```

Example:

```text
Font Size: 16px

16 × 1.5 = 24px

Line Height: 24px
```

The extra space helps the eye move naturally between lines and improves reading comfort.

---

## Heading Line Height

Large headings work differently.

Headings are scanned, not read like paragraphs, so they need tighter spacing.

Formula:

```text
Heading Line Height = Font Size × 1.2 – 1.3
```

Example:

```text
Font Size: 40px

40 × 1.2 = 48px

Line Height: 48px
```

If you use 1.5x for large headings:

```text
40px × 1.5 = 60px
```

The heading may feel disconnected because the space between lines becomes too large.

---

# Recommended System Values

| Type              | Font Size | Recommended Line Height | Scale Multiplier                            |
| :------------------ | :---------- | :------------------------ | :-------------------------------------------- |
| **H1**      | 40px      | 48px – 52px            | \~1.2x – 1.3x*(Tighter)*                 |
| **H2**      | 32px      | 38px – 42px            | \~1.2x – 1.3x                              |
| **H3**      | 24px      | 30px – 32px            | \~1.3x – 1.4x                              |
| **Body**    | 16px      | 24px                    | **1.5x** *(Optimal breathing room)* |
| **Caption** | 14px      | 18px – 22px            | \~1.4x – 1.5x                              |

---

# Letter Spacing

Letter spacing controls the space between characters.

It can affect readability and visual style.

Guidelines:

* Large headings may use slightly tighter spacing
* Small labels may use slightly wider spacing
* Body text usually stays close to default spacing

Avoid extreme values because they reduce readability.

---

# Visual Hierarchy

Visual hierarchy helps users understand what information matters most.

Typography creates hierarchy using:

* Size
* Weight
* Spacing
* Contrast

Example:

```text
Dashboard Analytics      H1

Monthly Performance      H2

Revenue Overview         H3

Supporting information   Body
```

Users should understand the structure without thinking about it.

---

# Content Width and Readability

Typography is also affected by text width.

A common readability guideline:

```text
45–75 characters per line
```

Why?

Very long lines:

* Make reading slower
* Make users lose their position

Very short lines:

* Make content feel broken

Good text width improves comprehension.

---

# Practical Example

Imagine you are designing a summary widget for an analytics dashboard.

---

## Poor Typography

> **Analytics**​*(16px / Regular)*
> **Monthly Report**​*(16px / Regular)*
> **Your data information**​*(16px / Regular)*

### The Problem

Because every line has identical weight, size, and scaling, the interface becomes a "wall of text".

The user's eye has no starting point, creating visual friction and making information harder to scan.

---

## Good Typography

> # **Analytics**​*(32px / Bold)*
> 
> ### **Monthly Report**​*(24px / Semi-Bold)*
> 
> Your data information... *(16px / Regular / Muted Color)*

### The Result

The hierarchy explains itself immediately.

Users understand:

* What is the main topic
* What is supporting information
* Where to focus first

A good typography system communicates structure before users even read the content.

---

# Common Typography Mistakes

## Using Too Many Fonts

Multiple fonts often create inconsistency.

## Poor Contrast

Low contrast reduces readability.

## Small Text

Very small text becomes difficult to read.

## Random Sizes

Inconsistent sizes weaken hierarchy.

## Same Line Height Everywhere

Headings and paragraphs need different spacing.

## Overusing Bold

When everything is emphasized, nothing stands out.

---

# Accessibility Considerations

Typography should work for all users.

Best practices:

* Use readable font sizes
* Maintain enough contrast
* Avoid long uppercase paragraphs
* Use clear hierarchy
* Test across screen sizes

Accessibility improves the experience for everyone.

---

# Lesson Checklist

Before moving to the next lesson, make sure you understand:

* What typography is
* Why typography matters
* How to choose fonts
* Typography scales
* Font sizes
* Font weights
* Line height rules
* Heading vs body spacing
* Letter spacing
* Visual hierarchy
* Common mistakes
* Accessibility principles

---



