## Valeriy Shesternin

### Contact information

- **Location:** Chelyabinsk, Russia
- **Github:** <https://github.com/Serotonin-pepperonin>
- **Telegram:** <https://t.me/pepperonin>
- **Email:** <serotonin.pepperonin@gmail.com>

### About me

i've tried to find myself into a lot of things like sport, photo, filmmaking ect, but one day I realized that coding is the best for me. This day was five months ago and since then I have been studying a little Python, basic JS, CSS, HTML, React, Node, Express ect, but all of this has no structure. So my purpose of the course is to became a Front-end developer and do what I really love at my future work!

### My skills

- HTML, CSS basic
- JavaScript, React basic
- TypeScript, React Native beginning
- Node.js, Express beginning
- PostgreSQL beginning
- Python beginning
- Git, Github basic
- Figma, Photoshop basic

### Code example

Just a simple react slider with [swiper](https://swiperjs.com).

```js

import React from "react";
import { Swiper, SwiperSlide } from "swiper/react";
import { Pagination, Autoplay } from "swiper";

import "swiper/css";
import "swiper/css/pagination";
import "swiper/css/autoplay";

const slides = [
  "https://images.unsplash.com/photo-1661565883779-774d498a3a96?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80",
  "https://images.unsplash.com/photo-1661618727512-a746d51b94b5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80",
  "https://images.unsplash.com/photo-1661621769106-5a4b5cf1e902?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80",
];

export default function HeroBanner() {
  return (
    <Swiper
      rewind={true}
      pagination={{
        dynamicBullets: true,
      }}
      autoplay={{ delay: 3000 }}
      modules={[Pagination, Autoplay]}
      className="mySwiper"
    >
      {slides.map((slide, index) => (
        <SwiperSlide key={index}>
          <img src={slide} alt="slide" />
        </SwiperSlide>
      ))}
    </Swiper>
  );
}

```

### Work experience

I've got no work experience in dev, but I got a lot of motivation to change it!

### Education

- [Coderslang](https://js.coderslang.com) full course
- Some free beginner courses on [HTMLacademy](https://htmlacademy.ru), [Hexlet](https://ru.hexlet.io) ect.
- A lot of YouTube videos, articles, [learnjavascript.ru](https://learnjavascript.ru) stackoverflow pages.

### Languages

- English - B2 (I read and listen well, but I can't build sentences)
- Russian - Native




