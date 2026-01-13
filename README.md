<!-- ╔══════════════════════════════ BEG ══════════════════════════════╗ -->

<br>
<div align="center">
    <p>
        <img src="./assets/img/logo.png" alt="logo" style="" height="60" />
    </p>
</div>

<div align="center">
    <img src="https://img.shields.io/badge/v-0.0.3-black"/>
    <a href="https://github.com/mineui-org"><img src="https://img.shields.io/badge/🔥-@mineui-black"/></a>
    <br>
    <img src="https://img.shields.io/badge/coverage-~%25-brightgreen" alt="Test Coverage" />
    <img src="https://img.shields.io/github/issues/mineui-org/tokens?style=flat" alt="Github Repo Issues" />
    <img src="https://img.shields.io/github/stars/mineui-org/tokens?style=social" alt="GitHub Repo stars" />
</div>
<br>

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->



<!-- ╔══════════════════════════════ DOC ══════════════════════════════╗ -->

- ## Overview 👀

    - #### Why ?
        > To standardize the design system with 350+ pre-configured tokens (colors, spacing, typography, shadows) using HSL format and semantic naming.

    - #### When ?
        > When using [@mineui](https://github.com/mineui-org) and [@cruxjs](https://github.com/cruxjs-org) to build consistent, scalable design systems and component libraries.

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
            > 11 color palettes × 11 shades each. HSL format for easy manipulation.

            ```scss
            // Gray scale (12 shades)
            $gray-0   to $gray-11

            // Brand colors (11 shades each)
            $blue-1   to $blue-11
            $green-1  to $green-11
            $red-1    to $red-11
            $amber-1  to $amber-11
            $orange-1 to $orange-11
            $purple-1 to $purple-11
            $pink-1   to $pink-11
            $cyan-1   to $cyan-11
            $teal-1   to $teal-11
            $indigo-1 to $indigo-11
            ```

        - #### Spacing

            > Perfect scale from 0 to 64 (0px to 256px).

            ```scss
            $sp-0,  $sp-1,  $sp-2,  $sp-3,  $sp-4,  $sp-5,  $sp-6,
            $sp-7,  $sp-8,  $sp-9,  $sp-10, $sp-12, $sp-14, $sp-16,
            $sp-20, $sp-24, $sp-28, $sp-32, $sp-36, $sp-40,
            $sp-44, $sp-48, $sp-52, $sp-56, $sp-60, $sp-64
            ```

        - #### Typography

            > Font families, sizes, weights, line heights, letter spacing.

            ```scss
            // Families
            $font-sans, $font-serif, $font-mono, $font-arabic

            // Sizes
            $fs-xs to $fs-9xl

            // Weights
            $fw-thin to $fw-black

            // Line heights
            $lh-none to $lh-loose

            // Letter spacing
            $ls-tighter to $ls-widest
            ```

        - #### Borders

            > Widths and radius values.

            ```scss
            // Widths
            $bw-0 to $bw-8

            // Radius
            $br-none to $br-3xl, $br-full
            ```

        - #### Shadows

            > Realistic shadows for light and dark modes.

            ```scss
            // Light mode
            $shadow-xs, $shadow-sm, $shadow-base, $shadow-md,
            $shadow-lg, $shadow-xl, $shadow-2xl,  $shadow-inner

            // Dark mode
            $shadow-xs-dark to $shadow-2xl-dark
            ```

        - #### Z-Index

            > Layering system with semantic names.

            ```scss
            $z-0 to $z-50
            $z-dropdown, $z-sticky,  $z-fixed,   $z-backdrop,
            $z-modal,    $z-popover, $z-tooltip, $z-notification
            ```

        - #### Transitions

            > Durations and easing functions.

            ```scss
            // Durations
            $dur-instant to $dur-slowest

            // Easings
            $ease-linear, $ease-in, $ease-out, $ease-in-out,
            $ease-bounce, $ease-elastic
            ```

        - #### Opacity

            > 0% to 100% in useful increments.

            ```scss
            $opacity-0, $opacity-5, $opacity-10, $opacity-20,
            $opacity-25, $opacity-30, $opacity-40, $opacity-50,
            $opacity-60, $opacity-70, $opacity-75, $opacity-80,
            $opacity-90, $opacity-95, $opacity-100
            ```

        - #### Breakpoints

            > Responsive design breakpoints.

            ```scss
            $bp-xs: 0
            $bp-sm: 640px
            $bp-md: 768px
            $bp-lg: 1024px
            $bp-xl: 1280px
            $bp-2xl: 1536px
            ```

        - #### Sizes

            > Common component sizes.

            ```scss
            $size-xs to $size-2xl
            ```

        - #### Blur

            > Backdrop and effect blur values.

            ```scss
            $blur-none to $blur-3xl
            ```

        - #### Aspect Ratios

            > Common aspect ratios.

            ```scss
            $aspect-square, $aspect-video, $aspect-4-3,
            $aspect-21-9, $aspect-portrait, $aspect-auto
            ```

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