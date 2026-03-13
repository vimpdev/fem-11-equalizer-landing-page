# 🚀 Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE).  
The goal of this challenge is to build a responsive landing page and replicate the provided design as closely as possible.  
Frontend Mentor challenges help developers improve their HTML, CSS, and responsive design skills by building realistic UI projects.

---

## 🎬 Demo

![](./docs/demo.gif)

---

## 🎯 The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

---

## 📸 Screenshots

| 📱 Mobile | 📲 Tablet | 🖥️ Desktop |
| --- | --- | --- |
| ![](./docs/mobile-default.avif) | ![](./docs/tablet-default.avif) | ![](./docs/desktop-default.avif) |

### 🖥️Desktop interaction

![](./docs/desktop-interaction.avif)

---

## 🔗 Links

- 🌎 [Live site](https://vimpdev.github.io/fem-11-equalizer-landing-page/)
<!-- - 🧑‍💻 [View solution on Frontend Mentor](https://your-solution-url.com) -->

---

## ⚒️ Built with

- Semantic HTML5 markup
- Modern CSS
    - CSS Layers
    - Custom Properties
    - Logical Properties
    - Clamp for fluid typography
- Flexbox
- CSS Grid
- Mobile-first workflow

---

## 🧠 What I learned

During this project I focused on writing modern, scalable CSS and structuring styles in a way that resembles a real-world architecture.

One key improvement was organizing styles using CSS Layers:

```css
@layer reset, fonts, tokens, base, layout, components, utilities;
```

This approach helps control the cascade and organize styles in a predictable hierarchy:

- reset → normalize styles
- tokens → design variables
- base → global styles
- layout → structural layout rules
- components → reusable UI components
- utilities → small helper classes

I also practiced fluid typography using `clamp()`, which allows text to scale smoothly between breakpoints:
```css
.hero-title {
  font-size: clamp(2.5rem, 1.6rem + 3.84vw, 5.5rem);
}
```
Another important aspect was using logical properties (`margin-inline`, `block-size`, etc.), which makes layouts more adaptable to different writing modes and modern CSS practices.

---

## 📚 Resources

- ManzDev — [CSS Layers explanation](https://lenguajecss.com/cascada-css/especificidad/regla-layer/)

- Kevin Powell — [CSS Layers tutorial](https://youtu.be/NDNRGW-_1EE?si=7tMb2T2JIknrzEjm)


## 👩‍💻 Author

- Frontend Mentor &ndash; [@vimpdev](https://www.frontendmentor.io/profile/vimpdev)

---