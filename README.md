# Featured Products block for Magento

A block to display featured products in Magento.

## Use

Copy the files to your Magento project following the folder structure and define a `featured` attribute for the products. 

Add the following to your `app/etc/local.xml` file:

    <?xml version="1.0"?>
    <config>
        <global>
            ...
            <blocks>
                <catalog>
                    <rewrite>
                        <product_featured>Wikaina_Catalog_Block_Product_Featured</product_featured>
                    </rewrite>
                    <rewrite>
                        <category_view>Wikaina_Catalog_Block_Category_View</category_view>
                    </rewrite>
                </catalog>
            </blocks>
            ...
        </global>
        ...
    </config>


This module was written as part of a Magento project, and is provided without having been tested in other projects. Chances are that it won't work at first try, please report issues or questions in the [Issues section](https://github.com/naoisegolden/magento-featured-products-block/issues).

## License

This Magento Module is distributed under the [Open Software License (OSL 3.0)](http://opensource.org/licenses/osl-3.0.php).
