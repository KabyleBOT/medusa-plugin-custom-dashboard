# Medusa Plugin Dashboard by Assalas com feat [SpearDevs](https://speardevs.com)

The Medusa Plugin Dashboard streamlines your e-commerce tracking and management through a single, easy-to-use interface.

## Features

- Sales Overview: Keep track of your daily revenue, orders, and average order value with our sales graph.
- Activity Feed: Stay updated with the latest customer purchases on your store.
- Actionable Insights: Quickly identify orders to fulfill, shipments to send out, stock levels, returns, and swaps to manage.

---

## Prerequisites

Ensure that you have the Medusa backend set up. You can find the installation guide for the Medusa backend [here](https://docs.medusajs.com/development/backend/install).

Enable [categories](https://docs.medusajs.com/modules/products/categories)

---

## How to Install

1\. Run the following command in the directory of the Medusa backend:

```bash
npm install medusa-plugin-custom-dashboard
```

OR

```bash
yarn add medusa-plugin-custom-dashboard
```

2\. In `medusa-config.js` add the following at the end of the `plugins` array:

```js
const plugins = [
	// ...
	{
		resolve: `medusa-plugin-custom-dashboard`,
		options: {
			enableUI: true,
		},
	},
];
```
