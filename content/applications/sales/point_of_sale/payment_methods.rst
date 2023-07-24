:show-content:

====================
Hình thức thanh toán
====================

To add a payment method, you first need to create it. Go to :menuselection:`Điểm bán hàng -->
Configuration --> Payment Methods --> New`, and set a name. Check :guilabel:`Identify Customer` to
allow this payment method *exclusively* for registered customers.

Then, select the :guilabel:`Journal`. Choose :guilabel:`Cash` to use this payment method for cash
payments, or :guilabel:`Bank` to use it for card payments.

.. image:: payment_methods/payment-method.png
   :alt: Creating a new payment method for a POS.


Once the payment method is created, you can select it in your POS settings. To do so, go to the
:ref:`POS' settings <configuration/settings>`, click :guilabel:`Edit`, and add the payment method
under the :guilabel:`Payments` section.

.. toctree::
   :titlesonly:
   
