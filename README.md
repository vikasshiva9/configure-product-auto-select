# configure-product-auto-select
With this script , associated product auto select on product page in magento 1.9 all version

Go to app/design/frontend/{YOUR_THEME}/template/catalog/product/view/type/options/configurable.phtml

In configurable.phtml file, 

find below code and after paste github configurable.phtml code :-

```sh
var spConfig = new Product.Config(<?php echo $_jsonConfig ?>);
```

Save file and reindexed , clear cache from magento admin panel.

For any confusion mail on vikas_shiva9@rediffmail.com or visit https://vikasshiva.com

