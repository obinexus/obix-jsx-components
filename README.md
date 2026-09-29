# obix-jsx-components

> Previous name: `@obinexusltd/obix-jsx-components` — OBIX packages are named without an npm scope since decision D-102 (2026-09-29); the package, its version and its exports are unchanged.

> **Compatibility package.** `obix-jsx-components` is kept so that code and documents that import it keep resolving. It contains **no logic**: every export below is the export of [`obix-binding-jsx`](https://github.com/obinexus/obix-binding-jsx) under the old name. New code should import from `obix-binding-jsx`.

Old package: upstream:obix-jsx-components@abeba2b:.. Decision: `compat-shim` (documented name; listed in `obix-naming.json` (OBIX monorepo record) `legacyShims`) in `docs/recovery/migration-table.md` (OBIX monorepo record) — DOC-IMPORTED; 31 JSX factories (`obixButton`…); `as any` bridges removed; ad-hoc obixLink replaced by createLink..

## `obix-jsx-components`

| Old name | Is |
|---|---|
| `obixAccordion` | `obix-binding-jsx`.`obixAccordion` |
| `obixAlert` | `obix-binding-jsx`.`obixAlert` |
| `obixAutocomplete` | `obix-binding-jsx`.`obixAutocomplete` |
| `obixBreadcrumb` | `obix-binding-jsx`.`obixBreadcrumb` |
| `obixButton` | `obix-binding-jsx`.`obixButton` |
| `obixCard` | `obix-binding-jsx`.`obixCard` |
| `obixCheckbox` | `obix-binding-jsx`.`obixCheckbox` |
| `obixDatePicker` | `obix-binding-jsx`.`obixDatePicker` |
| `obixDropdown` | `obix-binding-jsx`.`obixDropdown` |
| `obixFileUpload` | `obix-binding-jsx`.`obixFileUpload` |
| `obixForm` | `obix-binding-jsx`.`obixForm` |
| `obixImage` | `obix-binding-jsx`.`obixImage` |
| `obixInput` | `obix-binding-jsx`.`obixInput` |
| `obixLink` | `obix-binding-jsx`.`obixLink` |
| `obixLoading` | `obix-binding-jsx`.`obixLoading` |
| `obixModal` | `obix-binding-jsx`.`obixModal` |
| `obixNavigation` | `obix-binding-jsx`.`obixNavigation` |
| `obixPagination` | `obix-binding-jsx`.`obixPagination` |
| `obixProgress` | `obix-binding-jsx`.`obixProgress` |
| `obixRadioGroup` | `obix-binding-jsx`.`obixRadioGroup` |
| `obixSearch` | `obix-binding-jsx`.`obixSearch` |
| `obixSelect` | `obix-binding-jsx`.`obixSelect` |
| `obixSlider` | `obix-binding-jsx`.`obixSlider` |
| `obixStepper` | `obix-binding-jsx`.`obixStepper` |
| `obixSwitch` | `obix-binding-jsx`.`obixSwitch` |
| `obixTable` | `obix-binding-jsx`.`obixTable` |
| `obixTabs` | `obix-binding-jsx`.`obixTabs` |
| `obixTextarea` | `obix-binding-jsx`.`obixTextarea` |
| `obixToast` | `obix-binding-jsx`.`obixToast` |
| `obixTooltip` | `obix-binding-jsx`.`obixTooltip` |
| `obixVideo` | `obix-binding-jsx`.`obixVideo` |

Types: `ObixAccordionProps`, `ObixAlertProps`, `ObixAutocompleteProps`, `ObixBreadcrumbProps`, `ObixButtonProps`, `ObixCardProps`, `ObixCheckboxProps`, `ObixDatePickerProps`, `ObixDropdownProps`, `ObixFileUploadProps`, `ObixFormProps`, `ObixImageProps`, `ObixInputProps`, `ObixLinkProps`, `ObixLoadingProps`, `ObixModalProps`, `ObixNavigationProps`, `ObixPaginationProps`, `ObixProgressProps`, `ObixRadioGroupProps`, `ObixSearchProps`, `ObixSelectProps`, `ObixSliderProps`, `ObixStepperProps`, `ObixSwitchProps`, `ObixTableProps`, `ObixTabsProps`, `ObixTextareaProps`, `ObixToastProps`, `ObixTooltipProps`, `ObixVideoProps`.

## `obix-jsx-components/primitives`

| Old name | Is |
|---|---|
| `obixButton` | `obix-binding-jsx`.`obixButton` |
| `obixCard` | `obix-binding-jsx`.`obixCard` |
| `obixImage` | `obix-binding-jsx`.`obixImage` |
| `obixLink` | `obix-binding-jsx`.`obixLink` |
| `obixVideo` | `obix-binding-jsx`.`obixVideo` |

Types: `ObixButtonProps`, `ObixCardProps`, `ObixImageProps`, `ObixLinkProps`, `ObixVideoProps`.

## `obix-jsx-components/forms`

| Old name | Is |
|---|---|
| `obixCheckbox` | `obix-binding-jsx`.`obixCheckbox` |
| `obixDatePicker` | `obix-binding-jsx`.`obixDatePicker` |
| `obixFileUpload` | `obix-binding-jsx`.`obixFileUpload` |
| `obixForm` | `obix-binding-jsx`.`obixForm` |
| `obixInput` | `obix-binding-jsx`.`obixInput` |
| `obixRadioGroup` | `obix-binding-jsx`.`obixRadioGroup` |
| `obixSelect` | `obix-binding-jsx`.`obixSelect` |
| `obixTextarea` | `obix-binding-jsx`.`obixTextarea` |

Types: `ObixCheckboxProps`, `ObixDatePickerProps`, `ObixFileUploadProps`, `ObixFormProps`, `ObixInputProps`, `ObixRadioGroupProps`, `ObixSelectProps`, `ObixTextareaProps`.

## `obix-jsx-components/navigation`

| Old name | Is |
|---|---|
| `obixBreadcrumb` | `obix-binding-jsx`.`obixBreadcrumb` |
| `obixNavigation` | `obix-binding-jsx`.`obixNavigation` |
| `obixPagination` | `obix-binding-jsx`.`obixPagination` |
| `obixStepper` | `obix-binding-jsx`.`obixStepper` |
| `obixTabs` | `obix-binding-jsx`.`obixTabs` |

Types: `ObixBreadcrumbProps`, `ObixNavigationProps`, `ObixPaginationProps`, `ObixStepperProps`, `ObixTabsProps`.

## `obix-jsx-components/overlays`

| Old name | Is |
|---|---|
| `obixDropdown` | `obix-binding-jsx`.`obixDropdown` |
| `obixModal` | `obix-binding-jsx`.`obixModal` |
| `obixTooltip` | `obix-binding-jsx`.`obixTooltip` |

Types: `ObixDropdownProps`, `ObixModalProps`, `ObixTooltipProps`.

## `obix-jsx-components/feedback`

| Old name | Is |
|---|---|
| `obixAlert` | `obix-binding-jsx`.`obixAlert` |
| `obixLoading` | `obix-binding-jsx`.`obixLoading` |
| `obixProgress` | `obix-binding-jsx`.`obixProgress` |
| `obixToast` | `obix-binding-jsx`.`obixToast` |

Types: `ObixAlertProps`, `ObixLoadingProps`, `ObixProgressProps`, `ObixToastProps`.

## `obix-jsx-components/controls`

| Old name | Is |
|---|---|
| `obixSlider` | `obix-binding-jsx`.`obixSlider` |
| `obixSwitch` | `obix-binding-jsx`.`obixSwitch` |

Types: `ObixSliderProps`, `ObixSwitchProps`.

## `obix-jsx-components/data`

| Old name | Is |
|---|---|
| `obixAccordion` | `obix-binding-jsx`.`obixAccordion` |
| `obixTable` | `obix-binding-jsx`.`obixTable` |

Types: `ObixAccordionProps`, `ObixTableProps`.

## `obix-jsx-components/search`

| Old name | Is |
|---|---|
| `obixAutocomplete` | `obix-binding-jsx`.`obixAutocomplete` |
| `obixSearch` | `obix-binding-jsx`.`obixSearch` |

Types: `ObixAutocompleteProps`, `ObixSearchProps`.

## Verification

`test/shim.test.mjs` imports both packages and asserts, for every entry point: each old name is **identical** (`===`) to the owner's export (or, for the derived `renderX`, behaves as `renderWith(createX)`); the shim exports exactly these names and nothing else; every excluded name is absent. Verified on Node 26.7 only.

<!-- obix-release:begin — generated by scripts/release/prepare.mjs; edit the text above this line -->

## Installation

```bash
npm install obix-jsx-components
```

## Basic usage

```js
// existing code keeps working under the old name…
import { obixAccordion, obixAlert, obixAutocomplete } from 'obix-jsx-components';
// …new code imports the owner: obix-binding-jsx
```

## API surface

- `obix-jsx-components` — 31 value exports: `obixAccordion`, `obixAlert`, `obixAutocomplete`, `obixBreadcrumb`, `obixButton`, `obixCard`, `obixCheckbox`, `obixDatePicker`, `obixDropdown`, `obixFileUpload`, `obixForm`, `obixImage`, `obixInput`, `obixLink`, `obixLoading`, `obixModal`, `obixNavigation`, `obixPagination`, `obixProgress`, `obixRadioGroup`, `obixSearch`, `obixSelect`, `obixSlider`, `obixStepper`, `obixSwitch`, `obixTable`, `obixTabs`, `obixTextarea`, `obixToast`, `obixTooltip`, `obixVideo`
- `obix-jsx-components/primitives` — 5 value exports: `obixButton`, `obixCard`, `obixImage`, `obixLink`, `obixVideo`
- `obix-jsx-components/forms` — 8 value exports: `obixCheckbox`, `obixDatePicker`, `obixFileUpload`, `obixForm`, `obixInput`, `obixRadioGroup`, `obixSelect`, `obixTextarea`
- `obix-jsx-components/navigation` — 5 value exports: `obixBreadcrumb`, `obixNavigation`, `obixPagination`, `obixStepper`, `obixTabs`
- `obix-jsx-components/overlays` — 3 value exports: `obixDropdown`, `obixModal`, `obixTooltip`
- `obix-jsx-components/feedback` — 4 value exports: `obixAlert`, `obixLoading`, `obixProgress`, `obixToast`
- `obix-jsx-components/controls` — 2 value exports: `obixSlider`, `obixSwitch`
- `obix-jsx-components/data` — 2 value exports: `obixAccordion`, `obixTable`
- `obix-jsx-components/search` — 2 value exports: `obixAutocomplete`, `obixSearch`
- Type declarations: `./dist/index.d.ts` (and a declaration next to every JS entry point).

## Architecture role

`obix-jsx-components` is a **compatibility package**: it keeps an old name resolving and contains no logic — every export is the export of [`obix-binding-jsx`](https://github.com/obinexus/obix-binding-jsx). New code imports from `obix-binding-jsx` (or from the umbrella `obix`).

The architecture of OBIX — the package families and which packages are public API — is indexed in the umbrella: [docs/architecture.md](https://github.com/obinexus/obix/blob/main/docs/architecture.md).

## Package relationships

- Depends on (OBIX): [`obix-binding-jsx`](https://github.com/obinexus/obix-binding-jsx).
- Used by (OBIX): no other OBIX package.

## Testing

- 1 test file ships in the npm package (`test/`): the evidence of the package's contract, published so that its verification can be inspected — not runtime code (no entry point reaches it).
- **Standalone**: 1 of 1 — it reads nothing outside the package.
- Run them with `npm test` (`node --test "test/*.test.mjs"`) in the OBIX monorepo, which provides the test tooling (Node's test runner, TypeScript) and the harness.

## Documentation

- [CHANGELOG.md](CHANGELOG.md)
- The OBIX architecture index: [obix/docs/architecture.md](https://github.com/obinexus/obix/blob/main/docs/architecture.md)

## Repository

- https://github.com/obinexus/obix-jsx-components — `git@github.com:obinexus/obix-jsx-components.git`
- Issues: https://github.com/obinexus/obix-jsx-components/issues
- The repository is a clean export of the package from the OBIX monorepo. Its lineage — the sources it was recovered from and its earlier names — is `PROVENANCE.json`, shipped in this package; the repository's copy also records the monorepo commit it was exported from.

## License

MIT — see [LICENSE](LICENSE).

<!-- obix-release:end -->
