---
title: Enabling Inventory Management
redirect_from: 
  - /catalog/settings-advanced-advanced-inventory.html
---

To manage your product inventory, enable Inventory Management at the global store or product level. When the **Manage Stock** option is enabled, Magento Inventory Management automatically tracks product quantities available for the site through configured stocks and sources. Every feature and option begins tracking and reporting when enabled, without additional configuration.

Your business runs and inventory updates at the speed of sales. As customers shop, you receive exact, updated information for available stock per sales channel and source. Available salable quantities update per stock when customers add products to cart and complete purchases and when and you manage orders, create shipments, and issue refunds. Arrivals of new or transferred stock update to your sources, immediately available for online sales. Backorders complete up to specified thresholds without infinite orders or additional configurations. And you enter and complete partial or full shipments across one or more sources with recommendations, giving you complete control over order fulfillment and on-hand inventory.

{:.bs-callout .bs-callout-info}
By default, Inventory Management is enabled when installing or upgrading Magento. Depending on your business needs, you may want to enable or disable Magento tracked Inventory Management.

How this setting works in Single and Multi Source inventories:

- To use Magento Inventory Management, enable Manage Stock.

- Manage Stock settings at the product level override the store configuration.

- To use Magento Order Management or third party services such as ERP, disable Manage Stock.

- If the product level configuration uses the system default, the store configuration overrides.

With Inventory Management enabled, see the following to configure all settings:

- [Configuring Global Options]({% link catalog/inventory-options-global.md %}): Settings that affect your entire catalog, considered the system default settings

- [Configuring Product Options]({% link catalog/inventory-product-stock-options.md %}): Settings for a specific product that override global options

## Enable or Disable Inventory Management

1. On the _Admin_ sidebar, go to **Stores** > _Settings_ < **Configuration**.

1. In the panel to the left, click **Catalog** and choose **Inventory**.

1. Expand ![]({% link images/images/btn-expand.png %}){: .Inline} the **Product Stock Options** section, and configure:

   - To manage inventory and use all Magento features, set **Manage Stock** to `Yes` (default).

   - To disable Magento Inventory Management, clear the **Use system value** checkbox and set **Manage Stock** to `No`.

1. When complete, click <span class="btn">Save Config</span>.

   ![]({% link images/images/config-catalog-catalog-inventory-product-stock-options.png %}){: .zoom}
   _[Product Stock Options]({% link configuration/catalog/inventory.md %})_

## Manage Stock for a Store

See [Configure Global Options]({% link catalog/inventory-options-global.md %}).

## Manage Stock for a Product

See [Configuring Product Options]({% link catalog/inventory-product-stock-options.md %}).
