### _[Signup free with 2Checkout and start selling!](https://www.2checkout.com/referral?r=git2co)_

### Integrate OpenCart with 2Checkout (Supports Direct Checkout)
----------------------------------------

### OpenCart Settings

1. Download the 2Checkout payment module from https://github.com/craigchristenson/opencart-2checkout
2. Upload the files to your OpenCart directory.
3. Sign in to your OpenCart admin.
4. Click **Extensions** tab and **Payments subtab**.
5. Under **2Checkout** click **Install** and then click **Edit**.
6. Enter your **2Checkout Account ID**. _(2Checkout Account Number)_
7. Select **No** under **Test Mode**.
8. Select **Yes** under **Checkout Display** if you want to use Inline Checkout.
9. Select **Complete** under **Order Status**.
10. Select **Enabled** under **Status**.
11. Enter your **Secret Word** _(Must be the same value entered on your 2Checkout Site Management page.)_
12. Save your changes.

### 2Checkout Settings

1. Sign in to your 2Checkout account. 
2. Click the **Account** tab and **Site Management** subcategory. 
3. Under **Direct Return** select **Header Redirect** or **Given links back to my website**.
4. Enter your **Secret Word**._(Must be the same value entered in your OpenCart admin.)_
5. Set the **Approved URL** to http://www.yourstore.com/index.php?route=payment/twocheckout/callback _(Replace http://www.yourstore.com with the actual URL to your store.)_
6. Click **Save Changes**. 

Please feel free to contact 2Checkout directly with any integration questions.
