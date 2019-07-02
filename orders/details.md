---
layout: tabs
title: Details Page
parent: Orders
has_children: false
permalink: orders/details/
tabs:
  - name: Shipments
    toc: true
    toc_header: On this tab
    context:
      - title: The Shipments Tab contains the sections below
        steps:
        - instruction: Overview information about the Order will appear on this section to the right of the screen including the orders' status and customer information
          image: /assets/images/mockdown/draft2/orders/details/details_shipments_information_dark_cropped.jpg
        - instruction: To add a product without using the Cart tab, Use this Add Product module in the Shipments tab
          image: /assets/images/mockdown/draft2/orders/details/details_shipments_add_product_dark_cropped.jpg
        - instruction: Review the Shipment information of the Package
          image: /assets/images/mockdown/draft2/orders/details/details_shipments_package_dark_cropped.jpg
        - instruction: Review the items in the cart of the Order and Edit the shipping method and tracking information
          image: /assets/images/mockdown/draft2/orders/details/details_shipments_cart_dark_cropped.jpg
        - instruction: Any Gift Card details will be shown in this section
          image: /assets/images/mockdown/draft2/orders/details/details_shipments_gift_card_dark_cropped.jpg
        - instruction: Review the recipient information
          image: /assets/images/mockdown/draft2/orders/details/details_shipments_recipient_dark_cropped.jpg
  - name: Cart
    toc: true
    toc_header: On this tab
    context:

      - title: Add an Item to an Order
        steps:

        - instruction: Open the Cart tab in the Details page of the order
          image: /assets/images/mockdown/draft2/orders/shipments/orders_new_cart.jpg

        - instruction: Locate the empty slot in the cart list and Click Choose a Variant and start typing the SKU or Product Title of the product you want to add to the order
          image: /assets/images/mockdown/draft2/orders/shipments/orders_new_cart_add_item_slot_dark.jpg

        - instruction: Click Save to add the item to the order
          image: /assets/images/mockdown/draft2/orders/shipments/orders_new_cart_add_item_save_dark.jpg

        - instruction: To add another item, click the Add Item button near the top of the tab
          image: /assets/images/mockdown/draft2/orders/shipments/orders_new_cart_add_item_dark.jpg

        - instruction: Locate the new empty slot in the cart and Click Choose a Variant and start typing the SKU or Product Title of the product you want to add to the order
          notes:
          - header: Keep repeating these steps to add more items to your order
          image: /assets/images/mockdown/draft2/orders/shipments/order_new_add_item_post_out_slot_dark.jpg

      - title: Delete an Item from an Order
        steps:

        - instruction: Open the Cart tab in the Details page of the order
          image: /assets/images/mockdown/draft2/orders/shipments/orders_new_cart.jpg

        - instruction: Hover your mouse over the an item in the cart and click Delete
          image: /assets/images/mockdown/draft2/orders/shipments/orders_cart_delete_dark.jpg

  - name: Customer
    toc: true
    toc_header: On this tab
    context:

      - title: How to attach a Customer to an Order
        steps:

        - instruction: Go to the Custmer tab
          image: /assets/images/mockdown/draft2/orders/shipments/orders_customer_tab_dark.jpg

        - instruction: 'To Attach a customer to the order:'
          images:
          - image_header: Select a customer from the drop down menu located at the top of the tab
            image: /assets/images/mockdown/draft2/orders/shipments/orders_customer_add_dark.jpg
          - image_header: Or fill in the information below
            image: /assets/images/mockdown/draft2/orders/shipments/orders_customer_full_information.jpg

        - instruction: Click Update at the bottom of the page
          image: /assets/images/mockdown/draft2/orders/shipments/orders_customer_bottom_update_dark.jpg

  - name: Adjustments
    toc: true
    toc_header: On this tab
    context:

      - title: How to Add an Ajustment
        steps:
        
        - instruction:  Go to the Adjustments tab
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_tab_dark.jpg

        - instruction:  New Adjustment Button
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_new_dark.jpg

        - instruction:  Fill in information
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_new_information.jpg
          
        - instruction:  Click Create
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_new_create_dark.jpg

        - instruction:  The New Adjustment will appear in the table below
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_new_post_slot_dark.jpg

        - instruction:  Click Finalize
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_new_post_finalize_dark.jpg

        - instruction:  Once you have finalized the new adjustments, the state of the adjustment will change to Locked
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_post_locked_out.jpg


      - title:  How to Edit or Delete an Adjustment
        steps:

        - instruction: Click Unfinalize Adjustments
          image: /assets/images/mockdown/draft2/orders/adjustments/adjustments_unfinalize.jpg

        - instruction: Click Edit or Delete on the Adjustments you want
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_edit_delete_dark.jpg

        - instruction:  Click Finalize
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_new_post_finalize_dark.jpg

        - instruction:  Once you have finalized the new adjustments, the state of the adjustment will change to Locked
          image:  /assets/images/mockdown/draft2/orders/adjustments/adjustments_post_locked_out.jpg

  - name: Payments
  - name: RMA
  - name: Customer Returns
  - name: Cancel Items
---

      - title: Open the Cart tab of an Order
        steps:

        - instruction: Go the Orders Homepage
          image: /assets/images/mockdown/draft2/orders/shipments/orders_home_out_orders_title.jpg

        - instruction: Locate the Orders List to the left of the page and select an order
          image: /assets/images/mockdown/draft2/orders/shipments/order_home_orders_list.jpg

        - instruction: The right side of the page will open the overview information of the Order
          image: /assets/images/mockdown/draft2/orders/shipments/order_home_orders_overview_dark.jpg

        - instruction: Click Details to open the details page of the order
          image: /assets/images/mockdown/draft2/orders/shipments/order_home_orders_details_button_dark.jpg

        - instruction: Click on the Cart tab
          image: cart_tab_dark_cropped.jpg