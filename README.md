## 🏷️ github-label-presets

Curated label presets for [@financial-times/github-label-sync](https://github.com/financial-times/github-label-sync).

&nbsp;

## 📦 Installation

This package is available for all sorts of projects via the following package managers:

### 📦 — NPM:

```
npm install @facilitative/github-label-presets@v1.0.0 -D
```

### 🧶 — Yarn:

```
yarn add @facilitative/github-label-presets@v1.0.0 -D
```

### 📀 — PNPM:

```
pnpm add @facilitative/github-label-presets@v1.0.0 -D
```

&nbsp;

## 🪧 Usage

### ⚙️ Defaults

A few default presets are provided to get you started:

-   [all](src/all.json)
-   [cla](src/cla.json)
-   [default](src/default.json) - _Default GitHub Labels_
-   [languages](src/languages.json)
-   [priority](src/priority.json)
-   [status](src/status.json)
-   [type](src/type.json)

### 📂 Strictly Typed

If you are looking to strictly use one format, consider using these instead (hard clears any other labels):

-   [strict-cla](src/strict/cla.json)
-   [strict-default](src/strict/default.json) - _Default GitHub Labels_
-   [languages](src/strict/languages.json)
-   [strict-priority](src/strict/priority.json)
-   [strict-status](src/strict/status.json)
-   [strict-type](src/strict/type.json)

## 🗞️ With [@financial-times/github-label-sync](https://github.com/financial-times/github-label-sync)

```
github-label-sync --access-token XXXXXX --labels node_modules/@facilitative/github-label-presets/src/strict/default.json USERNAME/REPOSITORY_NAME
```

&nbsp;

## 📝 License

github-label-presets is licensed under the [MIT License](LICENSE.md).
