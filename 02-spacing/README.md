# Spacing System

Spacing is one of the most important foundations of UI design.

Before creating layouts, components, or visual styles, designers must understand how to organize space effectively.

Spacing is not simply leaving empty areas between elements. In UI design, spacing is a system used to create relationships, improve readability, guide attention, and make interfaces easier to understand.

A strong spacing system is built around:

* Consistency
* Visual hierarchy
* Structure
* Accessibility

---

# What You'll Learn

In this lesson, you'll learn:

* What spacing is and why it matters
* The principle of proximity
* Spacing as a system
* The 8-point grid system
* Spacing scales
* Spacing tokens
* Padding vs margin
* Internal vs external spacing
* Visual hierarchy through spacing
* Common spacing mistakes
* Accessibility considerations
* How to apply spacing decisions in real interfaces

---

# What is Spacing?

Spacing is the intentional use of empty space between interface elements.

In UI design, spacing controls:

* Relationships between elements
* Content grouping
* Visual balance
* Information structure
* User focus

These elements work together to determine how users understand and navigate an interface.

---

# Why Spacing Matters

Spacing directly impacts user experience.

Good spacing helps users:

* Understand relationships faster
* Scan information easier
* Identify important sections
* Reduce mental effort
* Navigate interfaces comfortably

Poor spacing can lead to:

* Visual clutter
* Confusing layouts
* Weak hierarchy
* Increased cognitive load

The goal of spacing is not to fill empty areas.

The goal is communication and clarity.

---

# The Principle of Proximity

One of the most important concepts in UI design is proximity.

Elements that are close together are perceived as related.

Elements that are separated by larger spaces are perceived as different groups.

Example:

```text
Name
Email
Phone
```

Users immediately understand these fields belong together.

Now compare:

```text
Name

Email


Settings
```

The larger gaps create a different relationship.

This principle comes from Gestalt Psychology and is one of the foundations of visual organization.

---

# Spacing as a System

Professional interfaces do not choose spacing values randomly.

Instead of using:

```text
13px

17px

22px

29px
```

Designers create spacing systems with predictable values.

A spacing system provides:

* Consistency across screens
* Faster design decisions
* Easier development
* Better scalability
* Better collaboration between designers and developers

---

# The 8-Point Grid System

The most common spacing system in modern UI design is the ​**8-point grid**​.

In this system, spacing values and component dimensions are based on multiples of 8.

Example:

```text
8px

16px

24px

32px

40px

48px

56px

64px
```

This creates a consistent visual rhythm across the entire interface.

---

## Why 8?

The number 8 is not random.

It provides a balance between flexibility and consistency.

### Consistency

A fixed spacing unit prevents random values and keeps layouts predictable.

### Scalability

Large interfaces can grow while maintaining the same visual language.

### Better Collaboration

Designers and developers can communicate using shared spacing values.

Instead of:

```text
Move this about 23px.
```

Teams can use:

```text
Use LG spacing.
```

### Screen Compatibility

The value 8 works well across different screen sizes because it creates predictable increments that are easy to scale.

---

## The 4px Exception

Most modern design systems use ​**8px as the main spacing foundation**​.

However, some small adjustments require more control.

Use **4px spacing** for micro-spacing such as:

* Icon-to-text gaps
* Small badges
* Compact controls
* Dense UI elements

General rule:

> Use **8px** for layout structure.
> 
> Use **4px** only for small internal adjustments.

---

# Spacing Scale

A spacing scale is a predefined set of spacing values used consistently throughout a product.

Instead of creating random gaps between elements, designers use calculated spacing tokens.

---

## The Standard Spacing Scale

| Token         | Value (Px) | Scale Multiplier  | Common UI Usage                                                     |
| :-------------- | :----------- | :------------------ | :-------------------------------------------------------------------- |
| **XS**  | 4px        | \$0.5 \\times 8\$ | Tiny gaps, spacing between an icon and text                         |
| **SM**  | 8px        | \$1.0 \\times 8\$ | Tight spacing, inside form fields, chip padding                     |
| **MD**  | 16px       | \$2.0 \\times 8\$ | ​**Default spacing**​, standard card padding, body elements |
| **LG**  | 24px       | \$3.0 \\times 8\$ | Space between related cards, medium section titles                  |
| **XL**  | 32px       | \$4.0 \\times 8\$ | Major separation between distinct content blocks                    |
| **2XL** | 48px       | \$6.0 \\times 8\$ | Large padding for hero sections or headers                          |
| **3XL** | 64px       | \$8.0 \\times 8\$ | Page-level spacing                                                  |

---

# Padding vs. Margin

One of the most common beginner mistakes is confusing Padding and Margin.

Although both create empty space, they have different purposes.

---

## Padding (Internal Spacing)

Padding is the space inside a component.

Example:

```text
┌──────────────────────┐
│      Padding         │
│   ┌──────────────┐   │
│   │ Button Text  │   │
│   └──────────────┘   │
└──────────────────────┘
```

Padding affects:

* Component size
* Clickable area
* Internal comfort
* Accessibility

---

## Margin (External Spacing)

Margin is the space outside a component.

Example:

```text
┌──────────┐       ┌──────────┐
│ Button A │ Margin│ Button B │
└──────────┘       └──────────┘
```

Margin controls:

* Relationships between components
* Separation between sections
* Overall layout structure

---

# Internal vs External Spacing

Spacing can be divided into two categories.

## Internal Spacing

Controls content inside components.

Examples:

* Button padding
* Card padding
* Input spacing

---

## External Spacing

Controls distance between components.

Examples:

* Space between cards
* Space between sections
* Space between page areas

---

# Spacing and Visual Hierarchy

Spacing creates hierarchy just like typography.

It helps users understand:

* What is important
* What belongs together
* Where to look first

Example:

```text
Dashboard

Revenue Overview

Information
```

Compared to:

```text
Dashboard


Revenue Overview

Information
```

The second example creates stronger separation between sections.

General rule:

> Less space = Stronger relationship
> 
> More space = Weaker relationship

---

# Practical Example

Imagine designing a settings page.

## Poor Spacing

> **Profile**
> Name
> Email
> Password
> **Preferences**
> Language
> Theme

### The Problem

The spacing between every element is identical.

The brain cannot immediately understand which elements belong together.

The user must read everything instead of scanning the structure.

---

## Good Spacing

> ### **Profile**
> 
> Name
> Email
> Password
> 
> *(Space: 32px — XL)*
> 
> ### **Preferences**
> 
> Language
> Theme

### The Result

The layout becomes self-explanatory.

The user understands the structure immediately using the ​**Principle of Proximity**​.

Small gaps connect related elements.

Large gaps separate different sections.

---

# Common Spacing Mistakes

## Using Random Values

Avoid:

```text
11px

17px

23px
```

Use spacing tokens instead.

---

## Overcrowded Layouts

Too little spacing makes interfaces difficult to scan.

---

## Too Much Empty Space

Excessive spacing can disconnect related elements.

---

## Inconsistent Component Padding

Different padding values make interfaces feel unfinished.

---

## Using Borders Instead of Spacing

Many beginners use borders everywhere.

Often spacing alone can communicate structure better.

---

# Accessibility Considerations

Spacing should work for all users.

Best practices:

* Keep enough space between interactive elements
* Create comfortable touch areas
* Avoid crowded layouts
* Maintain consistent patterns
* Test different screen sizes

Good spacing improves usability for everyone.

---

# Lesson Checklist

Before moving to the next lesson, make sure you understand:

* What spacing is
* Why spacing matters
* The principle of proximity
* 8-point grid system
* Spacing scales
* Spacing tokens
* Padding vs margin
* Internal vs external spacing
* Hierarchy through spacing
* Common spacing mistakes
* Accessibility principles

---



