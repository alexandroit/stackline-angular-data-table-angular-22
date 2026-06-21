# @stackline/angular-data-table-component Angular 22 Playground

StackBlitz playground for the Angular 22 line of `@stackline/angular-data-table-component`.

This project installs `@stackline/angular-data-table-component@22.0.0` against Angular `22.0.2`.

The examples are organized like a normal Angular app, with one folder and one component per feature:

```text
src/app/examples/basic/basic.component.ts
src/app/examples/basic/basic.component.html
src/app/examples/basic/basic.component.css
```

Shared data, table models, layout helpers, and source loading live in clear shared folders:

```text
src/app/models/
src/app/services/
src/app/shared/
```

## Routes

| Example | Route |
| --- | --- |
| Basic usage | `/basic` |
| Sortable columns | `/sorting` |
| Multi selection | `/multi-selection` |
| Single selection | `/single-selection` |
| Programmatic selection | `/programmatic-selection` |
| Disabled selectable rows | `/disabled-selection` |
| Client pagination | `/client-pagination` |
| Server pagination | `/server-pagination` |
| Visible page selection | `/visible-page-selection` |
| Fixed header | `/fixed-header` |
| Conditional styles | `/conditional-styles` |
| Custom cell templates | `/cell-templates` |
| Expandable rows | `/expandable-rows` |
| Expand on row click | `/expand-on-click` |
| Row events | `/row-events` |
| Dense layout | `/dense` |
| Dark theme | `/dark` |
| Loading state | `/loading` |
| Empty state | `/empty` |
| Headerless table | `/headerless` |
| Responsive and wrapped cells | `/responsive-wrap` |
| Global filtering | `/global-filtering` |
| Column filtering | `/column-filtering` |
| Column visibility | `/column-visibility` |
| Column ordering | `/column-ordering` |
| Column pinning | `/column-pinning` |
| Row pinning | `/row-pinning` |
| Grouping | `/grouping` |
| Header groups | `/header-groups` |
| Faceted values | `/faceting` |
| Column sizing | `/column-sizing` |
| Virtual rows | `/virtual-rows` |
| Kitchen sink | `/kitchen-sink` |
| Accessibility and keyboard | `/accessibility-keyboard` |
| Large data pagination | `/large-data-pagination` |
| Image cells | `/image-cells` |
| Headless custom HTML | `/headless-html` |
| HttpClient data | `/http-client-data` |
| Animated rows | `/animated-rows` |
| Async pipe stream | `/async-pipe-stream` |

## Run

```bash
npm install
npm start
```

`npm start` is StackBlitz-safe. It starts the Angular CLI dev server when the runtime supports Angular 22, and serves the committed preview build when the WebContainer Node version is older than Angular 22 requires.

Use this command when you specifically want the real Angular CLI dev server:

```bash
npm run dev
```

Angular 22 CLI requires Node `22.22.3+`, `24.15.0+`, or `26.0.0+`.

## StackBlitz

```text
https://stackblitz.com/github/alexandroit/stackline-angular-data-table-angular-22?startScript=start
```

Open a specific route by adding `initialpath`:

```text
https://stackblitz.com/github/alexandroit/stackline-angular-data-table-angular-22?startScript=start&initialpath=%2Fbasic
```

## Links

- Docs: https://alexandro.net/docs/angular/angular-data-table-component/angular-22/
- npm: https://www.npmjs.com/package/@stackline/angular-data-table-component
- GitHub package repo: https://github.com/alexandroit/angular-data-table-component
