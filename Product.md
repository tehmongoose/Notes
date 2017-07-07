<h3><b>Product Catalog</b></h3>
* **Name**
* **Description**
* **Products**
>* Active Products
>* Inactive Products
>* In-development Products

* **Who are these products for?**
	>How do you descript them? (tenant / partner / channel / region / blah?)

* **Offers** 
	>* Active Offers
	>* Inactive Offers
	>* In-development Offers

<h3><b>Product</b></h3>
* **Name**
* **Description**
* **Expiration** (how long is it view-able maybe??)
* **Base cost** (???)
* **Features**


<h3><b>Feature</b></h3>
* **Name**
* **Description**
	>* short
	>* long
	>* translations?
	
* **How you fulfill it?**
	>* Where do you go to get it?
	>* How many times can you fulfill it?
		* subscription
			* daily/weekly/monthly auto fulfills
			* on-demand
		* transaction
			* on-demand
			* bundles (you get 3 credit reports whenever you click "get a new one")

* What is the minimum criteria you need to have it?
	>* Where can you buy it?
	>* Who can have it?
	>* What authorization do you need to have it?


<h3><b>Offer</b></h3>
* Product 
	* What are we getting?
* Price
	* How much does it cost?
* Term
	* How long do you get it?


<h3><b>Discount</b></h3>
* Applicable products
* Percent discount
* flat discount
* # free trial days?
* Stacking OR sequential
* Expiration 


<h3><b>Order</b></h3>
* A list of Offers
* state
	* prospective 
	* abandoned 
	* attempted (can't, failed)
	* failed (fraud, bad payment, usage criteria not met)
	* fulfilled?

**What about subscriptions**? Does the order live on?
	- Line items per <something>??? how do we repose this?
	- Is this line item per fulfillible, so a line item per feature? 
	**Example:**
	
	fulfilled credit report (id 1)
	fulfilled credit report (id: 2)
	failed to fulfill credit report
	re-try (1) to fulfill credit report
	re-try (2)  to fulfill credit report
	fulfilled credit report (id: 3)


<h3><b>Some random processes</b></h3>
	Fulfillment - 
		Input: 
			An Order
		Output: 
			An Updated Order ?? 

