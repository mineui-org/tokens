<!-- ╔══════════════════════════════ BEG ══════════════════════════════╗ -->

<br>
<div align="center">
    <p>
        <img src="./assets/img/logo.png" alt="logo" style="" height="60" />
    </p>
</div>

<div align="center">
    <img src="https://img.shields.io/badge/v-0.0.9-black"/>
    <a href="https://github.com/mineui-org"><img src="https://img.shields.io/badge/🔥-@mineui-black"/></a>
    <br>
    <img src="https://img.shields.io/github/issues/mineui-org/tokens?style=flat" alt="Github Repo Issues" />
    <img src="https://img.shields.io/github/stars/mineui-org/tokens?style=social" alt="GitHub Repo stars" />
</div>
<br>

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->



<!-- ╔══════════════════════════════ DOC ══════════════════════════════╗ -->

- ## Overview 👀

    - #### Why ?
        > Complete design tokens system with 350+ values covering colors, spacing, typography, shadows, and more. Built for modern UI systems with HSL colors and short, friendly names.

    - #### When ?
        > Use as the foundation for any CSS/SCSS project. Perfect for design systems, component libraries, or custom UI frameworks.

    <br>
    <br>

- ## Quick Start 🔥

    > install [`hmm`](https://github.com/minejs-org/hmm) first.

    ```bash
    # in your terminal
    hmm i @mineui/tokens
    ```

    ```scss
    # in your `.scss` files
    @use "./node_modules/@mineui/tokens/dist/scss/index.scss" as *;
    ```

    <div align="center"> <img src="./assets/img/line.png" alt="line" style="display: block; margin-top:20px;margin-bottom:20px;width:500px;"/> </div>
    <br>

    - ### Colors

        ```scss
        .button {
          background    : $blue-6;  // Main blue
          color         : $gray-0;  // Almost white
          border        : 1px solid $gray-3;
        }
        ```

    - ### Spacing & Typography

        ```scss
        .card {
          padding       : $sp-6;        // 1.5rem (24px)
          font-size     : $fs-lg;       // 1.125rem (18px)
          font-weight   : $fw-medium;   // 500
          border-radius : $br-lg;       // 0.5rem (8px)
        }
        ```

    <br>
    <br>

- ## Documentation 📑

    - ### API ⛓️

        - #### Colors

            > 12 color palettes × 11 shades each. HSL format for easy manipulation.

            | Palette    | Shade 1     | Shade 2     | Shade 3     | Shade 4     | Shade 5     | Shade 6     | Shade 7     | Shade 8     | Shade 9     | Shade 10     | Shade 11     |
            | ---------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ------------ | ------------ |
            | **Gray**   | `$gray-0`   | `$gray-1`   | `$gray-2`   | `$gray-3`   | `$gray-4`   | `$gray-5`   | `$gray-6`   | `$gray-7`   | `$gray-8`   | `$gray-9`    | `$gray-10`   |
            | **Blue**   | `$blue-1`   | `$blue-2`   | `$blue-3`   | `$blue-4`   | `$blue-5`   | `$blue-6`   | `$blue-7`   | `$blue-8`   | `$blue-9`   | `$blue-10`   | `$blue-11`   |
            | **Green**  | `$green-1`  | `$green-2`  | `$green-3`  | `$green-4`  | `$green-5`  | `$green-6`  | `$green-7`  | `$green-8`  | `$green-9`  | `$green-10`  | `$green-11`  |
            | **Red**    | `$red-1`    | `$red-2`    | `$red-3`    | `$red-4`    | `$red-5`    | `$red-6`    | `$red-7`    | `$red-8`    | `$red-9`    | `$red-10`    | `$red-11`    |
            | **Amber**  | `$amber-1`  | `$amber-2`  | `$amber-3`  | `$amber-4`  | `$amber-5`  | `$amber-6`  | `$amber-7`  | `$amber-8`  | `$amber-9`  | `$amber-10`  | `$amber-11`  |
            | **Orange** | `$orange-1` | `$orange-2` | `$orange-3` | `$orange-4` | `$orange-5` | `$orange-6` | `$orange-7` | `$orange-8` | `$orange-9` | `$orange-10` | `$orange-11` |
            | **Purple** | `$purple-1` | `$purple-2` | `$purple-3` | `$purple-4` | `$purple-5` | `$purple-6` | `$purple-7` | `$purple-8` | `$purple-9` | `$purple-10` | `$purple-11` |
            | **Pink**   | `$pink-1`   | `$pink-2`   | `$pink-3`   | `$pink-4`   | `$pink-5`   | `$pink-6`   | `$pink-7`   | `$pink-8`   | `$pink-9`   | `$pink-10`   | `$pink-11`   |
            | **Cyan**   | `$cyan-1`   | `$cyan-2`   | `$cyan-3`   | `$cyan-4`   | `$cyan-5`   | `$cyan-6`   | `$cyan-7`   | `$cyan-8`   | `$cyan-9`   | `$cyan-10`   | `$cyan-11`   |
            | **Teal**   | `$teal-1`   | `$teal-2`   | `$teal-3`   | `$teal-4`   | `$teal-5`   | `$teal-6`   | `$teal-7`   | `$teal-8`   | `$teal-9`   | `$teal-10`   | `$teal-11`   |
            | **Indigo** | `$indigo-1` | `$indigo-2` | `$indigo-3` | `$indigo-4` | `$indigo-5` | `$indigo-6` | `$indigo-7` | `$indigo-8` | `$indigo-9` | `$indigo-10` | `$indigo-11` |

        - #### Spacing

            > Perfect scale from 0 to 64 (0–256px). Rem-based for responsive scaling.

            | Token    | Value   | Pixels |
            | -------- | ------- | ------ |
            | `$sp-0`  | 0       | 0px    |
            | `$sp-1`  | 0.25rem | 4px    |
            | `$sp-2`  | 0.5rem  | 8px    |
            | `$sp-3`  | 0.75rem | 12px   |
            | `$sp-4`  | 1rem    | 16px   |
            | `$sp-5`  | 1.25rem | 20px   |
            | `$sp-6`  | 1.5rem  | 24px   |
            | `$sp-7`  | 1.75rem | 28px   |
            | `$sp-8`  | 2rem    | 32px   |
            | `$sp-9`  | 2.25rem | 36px   |
            | `$sp-10` | 2.5rem  | 40px   |
            | `$sp-12` | 3rem    | 48px   |
            | `$sp-14` | 3.5rem  | 56px   |
            | `$sp-16` | 4rem    | 64px   |
            | `$sp-20` | 5rem    | 80px   |
            | `$sp-24` | 6rem    | 96px   |
            | `$sp-28` | 7rem    | 112px  |
            | `$sp-32` | 8rem    | 128px  |
            | `$sp-36` | 9rem    | 144px  |
            | `$sp-40` | 10rem   | 160px  |
            | `$sp-44` | 11rem   | 176px  |
            | `$sp-48` | 12rem   | 192px  |
            | `$sp-52` | 13rem   | 208px  |
            | `$sp-56` | 14rem   | 224px  |
            | `$sp-60` | 15rem   | 240px  |
            | `$sp-64` | 16rem   | 256px  |

        - #### Typography

            > System fonts, scales, weights, line heights, and letter spacing.

            **Font Families:**

            | Variable       | Font Stack                                |
            | -------------- | ----------------------------------------- |
            | `$font-sans`   | System default (SF Pro, Segoe UI, Roboto) |
            | `$font-serif`  | Georgia, Cambria, Times New Roman         |
            | `$font-mono`   | SFMono, Menlo, Monaco, Consolas           |
            | `$font-arabic` | Cairo, Noto Sans Arabic                   |

            **Font Sizes:**

            | Token      | Value     | Pixels |
            | ---------- | --------- | ------ |
            | `$fs-xs`   | 0.75rem   | 12px   |
            | `$fs-sm`   | 0.875rem  | 14px   |
            | `$fs-base` | 1rem      | 16px   |
            | `$fs-md`   | 1.0625rem | 17px   |
            | `$fs-lg`   | 1.125rem  | 18px   |
            | `$fs-xl`   | 1.25rem   | 20px   |
            | `$fs-2xl`  | 1.5rem    | 24px   |
            | `$fs-3xl`  | 1.875rem  | 30px   |
            | `$fs-4xl`  | 2.25rem   | 36px   |
            | `$fs-5xl`  | 3rem      | 48px   |
            | `$fs-6xl`  | 3.75rem   | 60px   |
            | `$fs-7xl`  | 4.5rem    | 72px   |
            | `$fs-8xl`  | 6rem      | 96px   |
            | `$fs-9xl`  | 8rem      | 128px  |

            **Font Weights:**

            | Token            | Value |
            | ---------------- | ----- |
            | `$fw-thin`       | 100   |
            | `$fw-extralight` | 200   |
            | `$fw-light`      | 300   |
            | `$fw-normal`     | 400   |
            | `$fw-medium`     | 500   |
            | `$fw-semibold`   | 600   |
            | `$fw-bold`       | 700   |
            | `$fw-extrabold`  | 800   |
            | `$fw-black`      | 900   |

            **Line Heights:**

            | Token         | Value |
            | ------------- | ----- |
            | `$lh-none`    | 1     |
            | `$lh-tight`   | 1.25  |
            | `$lh-snug`    | 1.375 |
            | `$lh-normal`  | 1.5   |
            | `$lh-relaxed` | 1.625 |
            | `$lh-loose`   | 2     |

            **Letter Spacing:**

            | Token         | Value    |
            | ------------- | -------- |
            | `$ls-tighter` | -0.05em  |
            | `$ls-tight`   | -0.025em |
            | `$ls-normal`  | 0        |
            | `$ls-wide`    | 0.025em  |
            | `$ls-wider`   | 0.05em   |
            | `$ls-widest`  | 0.1em    |

        - #### Borders

            > Precise widths and radius values for consistent borders and shapes.

            **Border Widths:**

            | Token   | Value |
            | ------- | ----- |
            | `$bw-0` | 0     |
            | `$bw-1` | 1px   |
            | `$bw-2` | 2px   |
            | `$bw-3` | 3px   |
            | `$bw-4` | 4px   |
            | `$bw-6` | 6px   |
            | `$bw-8` | 8px   |

            **Border Radius:**

            | Token      | Value    | Pixels |
            | ---------- | -------- | ------ |
            | `$br-none` | 0        | 0px    |
            | `$br-sm`   | 0.125rem | 2px    |
            | `$br-base` | 0.25rem  | 4px    |
            | `$br-md`   | 0.375rem | 6px    |
            | `$br-lg`   | 0.5rem   | 8px    |
            | `$br-xl`   | 0.75rem  | 12px   |
            | `$br-2xl`  | 1rem     | 16px   |
            | `$br-3xl`  | 1.5rem   | 24px   |
            | `$br-full` | 9999px   | 100%   |

        - #### Shadows

            > Realistic and beautiful shadows for light and dark modes.

            **Light Mode Shadows:**

            | Token           | Description                            |
            | --------------- | -------------------------------------- |
            | `$shadow-xs`    | Subtle (1px offset, 5% opacity)        |
            | `$shadow-sm`    | Small (1px offset, 10% opacity)        |
            | `$shadow-base`  | Base (1px offset, 10% opacity)         |
            | `$shadow-md`    | Medium (4px offset, 10% opacity)       |
            | `$shadow-lg`    | Large (10px offset, 10% opacity)       |
            | `$shadow-xl`    | Extra Large (20px offset, 10% opacity) |
            | `$shadow-2xl`   | 2X Large (25px offset, 25% opacity)    |
            | `$shadow-inner` | Inset (internal shadow)                |
            | `$shadow-none`  | No shadow                              |

            **Dark Mode Shadows:**

            | Token               | Opacity |
            | ------------------- | ------- |
            | `$shadow-xs-dark`   | 30%     |
            | `$shadow-sm-dark`   | 40%     |
            | `$shadow-base-dark` | 40%     |
            | `$shadow-md-dark`   | 40%     |
            | `$shadow-lg-dark`   | 40%     |
            | `$shadow-xl-dark`   | 50%     |
            | `$shadow-2xl-dark`  | 60%     |

        - #### Z-Index

            > Layering system with numeric and semantic values.

            **Numeric Scale:**

            | Token     | Value |
            | --------- | ----- |
            | `$z-0`    | 0     |
            | `$z-1`    | 1     |
            | `$z-10`   | 10    |
            | `$z-20`   | 20    |
            | `$z-30`   | 30    |
            | `$z-40`   | 40    |
            | `$z-50`   | 50    |
            | `$z-auto` | auto  |

            **Semantic Values:**

            | Token             | Value | Use Case          |
            | ----------------- | ----- | ----------------- |
            | `$z-dropdown`     | 1000  | Dropdowns         |
            | `$z-sticky`       | 1020  | Sticky elements   |
            | `$z-fixed`        | 1030  | Fixed positioning |
            | `$z-backdrop`     | 1040  | Modal backdrops   |
            | `$z-modal`        | 1050  | Modal dialogs     |
            | `$z-popover`      | 1060  | Popovers          |
            | `$z-tooltip`      | 1070  | Tooltips          |
            | `$z-notification` | 1080  | Notifications     |

        - #### Transitions

            > Durations and easing functions for smooth animations.

            **Durations:**

            | Token           | Value |
            | --------------- | ----- |
            | `$dur-instant`  | 50ms  |
            | `$dur-fast`     | 100ms |
            | `$dur-normal`   | 150ms |
            | `$dur-moderate` | 200ms |
            | `$dur-slow`     | 300ms |
            | `$dur-slower`   | 500ms |
            | `$dur-slowest`  | 700ms |

            **Easing Functions:**

            | Token           | Curve       |
            | --------------- | ----------- |
            | `$ease-linear`  | Linear      |
            | `$ease-in`      | Ease In     |
            | `$ease-out`     | Ease Out    |
            | `$ease-in-out`  | Ease In-Out |
            | `$ease-bounce`  | Bounce      |
            | `$ease-elastic` | Elastic     |

        - #### Opacity

            > Transparency levels from 0% to 100%.

            | Token          | Value | Percentage |
            | -------------- | ----- | ---------- |
            | `$opacity-0`   | 0     | 0%         |
            | `$opacity-5`   | 0.05  | 5%         |
            | `$opacity-10`  | 0.1   | 10%        |
            | `$opacity-20`  | 0.2   | 20%        |
            | `$opacity-25`  | 0.25  | 25%        |
            | `$opacity-30`  | 0.3   | 30%        |
            | `$opacity-40`  | 0.4   | 40%        |
            | `$opacity-50`  | 0.5   | 50%        |
            | `$opacity-60`  | 0.6   | 60%        |
            | `$opacity-70`  | 0.7   | 70%        |
            | `$opacity-75`  | 0.75  | 75%        |
            | `$opacity-80`  | 0.8   | 80%        |
            | `$opacity-90`  | 0.9   | 90%        |
            | `$opacity-95`  | 0.95  | 95%        |
            | `$opacity-100` | 1     | 100%       |

        - #### Breakpoints

            > Mobile-first responsive design breakpoints.

            | Token     | Value  | Device      |
            | --------- | ------ | ----------- |
            | `$bp-xs`  | 0      | Extra Small |
            | `$bp-sm`  | 640px  | Small       |
            | `$bp-md`  | 768px  | Medium      |
            | `$bp-lg`  | 1024px | Large       |
            | `$bp-xl`  | 1280px | Extra Large |
            | `$bp-2xl` | 1536px | 2X Large    |

        - #### Sizes

            > Common component sizes for icons, buttons, and more.

            | Token        | Value  | Pixels |
            | ------------ | ------ | ------ |
            | `$size-xs`   | 1.5rem | 24px   |
            | `$size-sm`   | 2rem   | 32px   |
            | `$size-base` | 2.5rem | 40px   |
            | `$size-md`   | 3rem   | 48px   |
            | `$size-lg`   | 3.5rem | 56px   |
            | `$size-xl`   | 4rem   | 64px   |
            | `$size-2xl`  | 5rem   | 80px   |

        - #### Blur

            > Backdrop blur and visual effect values.

            | Token        | Value |
            | ------------ | ----- |
            | `$blur-none` | 0     |
            | `$blur-sm`   | 4px   |
            | `$blur-base` | 8px   |
            | `$blur-md`   | 12px  |
            | `$blur-lg`   | 16px  |
            | `$blur-xl`   | 24px  |
            | `$blur-2xl`  | 40px  |
            | `$blur-3xl`  | 64px  |

        - #### Aspect Ratios

            > Common aspect ratios for responsive images and layouts.

            | Token              | Ratio | Use Case         |
            | ------------------ | ----- | ---------------- |
            | `$aspect-square`   | 1:1   | Square content   |
            | `$aspect-video`    | 16:9  | Video/YouTube    |
            | `$aspect-4-3`      | 4:3   | Standard display |
            | `$aspect-21-9`     | 21:9  | Ultrawide        |
            | `$aspect-portrait` | 3:4   | Portrait images  |
            | `$aspect-auto`     | auto  | Intrinsic ratio  |

        <div align="center"> <img src="./assets/img/line.png" alt="line" style="display: block; margin-top:20px;margin-bottom:20px;width:500px;"/> </div>
        <br>

    - ### Related 🔗

        - ##### [@mineui/semantic](https://github.com/mineui-org/semantic)
            > Theme system and semantic variables built on these tokens

        - ##### [@mineui/core](https://github.com/mineui-org/core)
            > Complete UI framework using these tokens

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->



<!-- ╔══════════════════════════════ END ══════════════════════════════╗ -->

<br>
<br>

---

<div align="center">
    <a href="https://github.com/maysara-elshewehy"><img src="https://img.shields.io/badge/by-Maysara-black"/></a>
</div>

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->