# storeManager

[![Build Status](https://travis-ci.com/hogum/storeManager.svg?branch=master)](https://travis-ci.com/hogum/storeManager)

[![Coverage Status](https://coveralls.io/repos/github/hogum/storeManager/badge.svg)](https://coveralls.io/github/hogum/storeManager)

[![Code Climate](https://codeclimate.com/github/codeclimate/codeclimate/badges/gpa.svg)](https://codeclimate.com/github/hogum/storeManager)

[![GitHub issues](https://img.shields.io/github/issues/hogum/storeManager.svg?style=for-the-badge)](https://github.com/hogum/storeManager/issues)

A web application to help store managers maintain their inventories and manage sale records.


Try on Heroku: https://store-man90.herokuapp.com/stman/api/v1.0/products

/stman/api/v1.0/sales
GET sales 
POST sale
 
/stman/api/v1.0/sales/<int:sales_record>
GET sale
PUT sale
DELETE sale

/stman/api/v1.0/products
GET products, POST product

stman/api/v1.0/products/id
GET product, PUT, DELETE

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
