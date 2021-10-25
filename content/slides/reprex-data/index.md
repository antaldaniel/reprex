---
title: Slides
summary: Data Curation With Reprex
authors: []
tags: []
categories: []
date: "2020-01-21T00:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

# Data Curation With Reprex

[Reprex](https://wowchemy.com/) | [Data Curation](https://owchemy.com/docs/managing-content/#create-slides)

---

## Presentation Controls

- Next: `Right Arrow` or `Space`
- Previous: `Left Arrow`
- Start: `Home`
- Finish: `End`
- Overview: `Esc`
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- [PDF Export](https://github.com/hakimel/reveal.js#pdf-export): `E`

---

## Data observatories



## Data Curation

Our solution is a modern version of the data observatory, a permanent and highly automated data collection point. We use state-of-the-art data science and statistics to make sure that we get all the raw data needed and we put it into a truly usable form. Our automated data observatories perform all data processing, testing and correction work that humans find boring, unrewarding, not credited, and where they often fail. They serve as a human-centric interface to complex scientific software that only few specialists can use in the world.


---

## Fragments

Make content appear incrementally



{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

<Press `Space` to play!>

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}
- Only the speaker can read these notes
- Press `S` key to view
{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}
- Only the speaker can read these notes
- Press `S` key to view
{{< /speaker_note >}}

---

## Themes

- Data observatories: permanent data collection points
- We reviewed over 80 to compare their operations 
- Legal form, services, budget differs greatly
- No good use of statistical production and data science
- Started developing our Digital Music Observatory

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

<small>
- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links
</small>

---

{{< slide background-image="/media/boards.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/media/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://github.com/wowchemy/wowchemy-hugo-modules/discussions)

[Documentation](https://wowchemy.com/docs/managing-content/#create-slides)
