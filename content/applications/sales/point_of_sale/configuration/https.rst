=========================
Secure connection (HTTPS)
=========================

If **Direct Devices** is enabled in a Điểm bán hàng settings (for example, if you use an ePos
printer), HTTP becomes the default protocol.

Force your Điểm bán hàng to use a secure connection (HTTPS)
===========================================================

Add a new **key** in the **System Parameters** to force your Điểm bán hàng to use a secure
connection with the HTTPS protocol.

To do so, activate the :ref:`developer mode <developer-mode>`, go to :menuselection:`Settings -->
Technical --> Parameters --> System Parameters`, then create a new parameter, add the following
values and click on *Save*.

- **Key**: `point_of_sale.enforce_https`
- **Value**: `True`

.. seealso::
   - :doc:`epos_ssc`
