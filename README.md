# real-fake-product-generator
A Dunmanifestin palette for spoofing the Google Product Feed specification

Going off the [Products Feed Specification](https://support.google.com/merchants/answer/188494?hl=en), these are the details we've implemented:

- [x] Basic Product Information
- [x] Availability & Price
- [ ] Unique Product Identifiers
- [ ] Detailed Product Attributes and Item Groupings
- [ ] Tax & Shipping
- [ ] Product Combinations
- [x] Adult Products
- [ ] AdWords Attributes
- [ ] Custom Label Attributes for Shopping Campaigns
- [ ] Additional Attributes
- [ ] Unit Prices (US Only)
- [ ] Merchant Promotions Attribute


## Example

```
id	title	description	google product category	product type	link	mobile link	image link	additional	image link	condition	availability	availability date	price	sale price	sale price effective date
2	Mens Hat	Solid pink, queen-sized wand made of mithril made from 100% woven wool 300 thread count fabric. Set includes one fitted sheet, one flat sheet, and two standard pillowcases. Machine washable; extra deep fitted pockets.	6520	Office Supplies > Office Equipment > Electronic Dictionaries & Translators	http://www.example.com/asp/sp.asp?frog=12&id=1030	http://www.example.com/asp/sp.asp?eagle=12&id=1030	http://www.example.com/gryphon.jpg	http://www.example.com/tiger.jpg	refurbished	in stock	2014-12-25T13:00-0800	15.00 BAM	15.00 UZS	2014-12-25T13:00-0800/2014-12-25T13:00-0800
6	Mens Helmet	Solid white, queen-sized wand made of bone made from 100% woven cotton 300 thread count fabric. Set includes one fitted sheet, one flat sheet, and two standard pillowcases. Machine washable; extra deep fitted pockets.	5524	Cameras & Optics > Photography > Darkroom > Enlarging Equipment > Photographic Analyzers	http://www.example.com/asp/sp.asp?horse=12&id=1030	http://www.example.com/asp/sp.asp?lion=12&id=1030	http://www.example.com/hawk.jpg	http://www.example.com/owl.jpg	used	preorder	2014-12-25T13:00-0800	15.00 MRO	15.00 DZD	2014-12-25T13:00-0800/2014-12-25T13:00-0800
1	Mens Hat	Solid purple, queen-sized orb made from 100% woven horn 300 thread count fabric. Set includes one fitted sheet, one flat sheet, and two standard pillowcases. Machine washable; extra deep fitted pockets.	3107	Animals & Pet Supplies > Pet Supplies	http://www.example.com/asp/sp.asp?sheep=12&id=1030	http://www.example.com/asp/sp.asp?bat=12&id=1030	http://www.example.com/rat.jpg	http://www.example.com/sheep.jpg,http://www.example.com/turkey.jpg,http://www.example.com/horse.jpg,http://www.example.com/tiger.jpg,http://www.example.com/tiger.jpg,http://www.example.com/fox.jpg	refurbished	preorder	2014-12-25T13:00-0800	15.00 MXV	15.00 ZAR	2014-12-25T13:00-0800/2014-12-25T13:00-0800
```
