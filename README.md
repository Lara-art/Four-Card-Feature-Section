# Frontend Mentor - Four card feature section solution

This is my solution to the <a href="https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK"> Four card feature section on Frontend Mentor</a>.<br> Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Overview

### 💻 Screenshot

<table>
  <tr>
    <td style="width: 75%;"><img src="https://github.com/Lara-art/Four-Card-Feature-Section/blob/main/screenshot/Desktop.PNG" alt="Vista de Escritorio" style="width: 100%;"/></td>
    <td style="width: 25%;"><img src="https://github.com/Lara-art/Four-Card-Feature-Section/blob/main/screenshot/Mobile.PNG"  alt="Vista Móvil" style="width: 100%;"/></td>
  </tr>
</table>

### 🔗 Links

- Solution URL: [Github](https://github.com/Lara-art/Four-Card-Feature-Section)
- Live Site URL: [Deployed](https://lara-art.github.io/Four-Card-Feature-Section)

## My process

### 👩‍💻 Built with

- Web font import
- CSS custom properties
- Basic CSS reset
- Base typography settings
- Image styling
- Use of Flexbox
- Use of Grid
- Mobile-first design


### 📚 What I learned

With this exercise I learned that the grid is a bit difficult, I couldn't do it without @media.


```css
.grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}

@media (max-width:1000px) {

    .grid {
        grid-template-columns: 1fr;
    }
}


```
I couldn't get the height of .card to work without setting it directly. And as for the image position, the only way I could think of was to use position

```css

.card {
    padding: 2rem;
    height: 16rem;
    position: relative;

    & img {
        margin-top: 2rem;
        width: 80px;
        position: absolute;
        right: 10%;
        bottom: 15%;
    }
}
```


## ✨ Author

- Github - [Lara](https://github.com/Lara-art)
- Frontend Mentor - [@Lara-art](https://www.frontendmentor.io/profile/Lara-art)

## 📂 Repository

- All the challenges done: [Github](https://github.com/Lara-art/My-Frontend-Mentor-Repository)
