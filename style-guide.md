# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

#### Text

- Very dark desaturated blue: hsl(238, 29%, 16%)
- Soft red: hsl(14, 88%, 65%)

#### Gradient

Background gradient:

- Soft violet: hsl(273, 75%, 66%)
- Soft blue: hsl(240, 73%, 65%)

### Neutral

#### Text

- Very dark grayish blue: hsl(237, 12%, 33%)
- Dark grayish blue: hsl(240, 6%, 50%)

#### Dividers

- Light grayish blue: hsl(240, 5%, 91%)

## Typography

### Body Copy

- Font size: 12px

### Font

- Family: [Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans)
- Weights: 400, 700

& details {
        padding-bottom: 0.5em;

        & summary {
          display: flex;
          align-items: center;
          justify-content: space-between;
          cursor: pointer;
          list-style: none;
          padding: 1em 1em 1em 0em;

          & figure img {
            transition: ease-in 0.5ss;
            // transform: rotate(180deg);
          }
          &:focus {
            font-weight: $fw-700;
          }
        }
      }


    .details__container_item.is-expandable[open]
      .details__container_title:focus {
      & figure img {
        transition: transform 900ms ease;
        // transform: rotate(90deg);
      }
    }
    .details__container_item.is-expandable .details__container_title:focus {
      & figure img {
        transition: transform 900ms ease;
        transform: rotate(180deg);
      }
    }
