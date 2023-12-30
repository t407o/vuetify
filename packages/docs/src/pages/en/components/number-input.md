---
emphasized: true
meta:
  title: Number Input
  description: The Number input component is used for ...
  keywords: Number, vuetify number input component, vue number component
related:
  - /components/inputs/
  - /components/text-fields/
  - /components/forms/
features:
  label: 'C: VNumberInput'
  github: /components/VNumberInput/
  report: true
---

# Number Input

The VNumberInput extends the standard HTML number-type input, ensuring style consistency across browsers as a replacement for `<input type="number">`

![Otp input Entry](https://cdn.vuetifyjs.com/docs/images/components/v-otp-input/v-otp-input-entry.png)

<page-features />

::: success
This feature was introduced in [v3.4.0 (Blackguard)](/introduction/roadmap/#v3-4-blackguard)
:::

## Usage

Here we display a list of settings that could be applied within an application.

<usage name="v-otp-input" />

<entry />

## API

| Component | Description |
| - | - |
| [v-otp-input](/api/v-otp-input/) | Primary Component |

<api-inline hide-links />

## Anatomy

The `v-otp-input` component is a collection of [v-field](/api/v-field/) components that combine to create a single input.

![Otp input Anatomy](https://cdn.vuetifyjs.com/docs/images/components/v-otp-input/v-otp-input-anatomy.png "OTP input Anatomy")

| Element / Area | Description |
| - | - |
| 1. Container | The OTP input container holds a number of `v-field` components  |
| 2. Field | The `v-field` component is used to create a single input field |

## Guide

The `v-otp-input` component is a collection of `v-field` components that combine to create a single input. It is used to validate a one-time password (OTP) that is sent to the user via email or SMS.

The following code snippet is an example of a basic `v-otp-input` component.

```html
<v-otp-input></v-otp-input>
```

### Props

The `v-otp-input` component has support for most of `v-field`'s props and is follows the same design patterns as other inputs.

#### Length

The `length` prop determines the number of `v-field` components that are rendered. The default value is `6`.

<example file="v-otp-input/prop-length" />

#### Focus-all

The `autofocus` prop automatically focuses the first element in the `v-otp-input` component.

<example file="v-otp-input/prop-focus-all" />

#### Error

The `error` prop puts the `v-otp-input` into an error state. This is useful for displaying validation errors.

<example file="v-otp-input/prop-error" />

#### Variants

The `v-otp-input` component supports the same variants as `v-field`, `v-text-field` and other inputs.

<example file="v-otp-input/prop-variant" />

#### Loader

The `loader` prop displays a loader when the `v-otp-input` component is in a loading state. When complete, emits a `finish` event.

<example file="v-otp-input/prop-loader" />

## Examples

The following are a collection of examples that demonstrate more advanced and real world use of the `v-otp-input` component.

### Card variants

The following example is a detailed example of a `v-otp-input` component used within a card.

<example file="v-otp-input/misc-card" />

### Mobile text

The following example is a detailed example of a `v-otp-input` component used with mobile text.

<example file="v-otp-input/misc-mobile" />

### Verify account

The following example is a detailed example of a `v-otp-input` component used to verify a user's account.

<example file="v-otp-input/misc-verify" />

### Divider

The following example is a detailed example of a `v-otp-input` component used with a divider.

<example file="v-otp-input/misc-divider" />