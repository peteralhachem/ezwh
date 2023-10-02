
# Easy Warehouse - EZWH

A primitive exploitation of **NodeJS** for backend implementation, **ExpressJS** to build APIs, **Jest** and **Mocha** for unit and integration testing.



## Description 

Medium companies and retailers need a simple application to manage the relationship between the suppliers and their inventory of physical items stocked in a physical warehouse. The warehouse is supervised by a manager, who supervises the availability of items. When a certain item is in short supply, the manager issues an order to a supplier. In general the same item can be purchased by many suppliers. The warehouse keeps a list of possible suppliers per item.

After some time the items ordered to a supplier are received. The items must be quality checked and stored in specific positions in the warehouse. The quality check is performed by specific roles (quality office), who apply specific tests for item (different items are tested differently). Possibly the tests are not made at all, or made randomly on some of the items received. If an item does not pass a quality test it may be rejected and sent back to the supplier.

Storage of items in the warehouse must take into account the availability of physical space in the warehouse. Further the position of items must be traced to guide later recollection of them.

The warehouse is part of a company. Other organizational units (OU) of the company may ask for items in the warehouse. This is implemented via internal orders, received by the warehouse. Upon reception of an internal order the warehouse must collect the requested item(s), prepare them and deliver them to a pick up area. When the item is collected by the other OU the internal order is completed.

EZWH (Easy WareHouse) is a software application to support the management of a warehouse.
## Authors

- [@stefanodevenuto](https://github.com/stefanodevenuto)
- [@fabiooraziomirto](https://github.com/fabiooraziomirto)
- [@peteralhachem](https://github.com/peteralhachem)


## Badges


[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
![Static Badge](https://img.shields.io/badge/university-poliTO-green)

![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Mocha](https://img.shields.io/badge/-mocha-%238D6748?style=for-the-badge&logo=mocha&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)





## Tech Stack

- [NodeJS](https://nodejs.org/en)
- [ExpressJS](https://expressjs.com/)
- [Jest](https://jestjs.io/)
- [Mocha](https://mochajs.org/)


## Documentation

- [Initial version of Requirements](docs\RequirementsDocument.md)
- [Final version of Requirements](docs\OfficialRequirements.md)
- [Design](docs\DesignDocument.md)
- [API](docs\API.md)
- [Unit Testing](docs\UnitTestReport.md)
- [API Testing](docs\ApiTestReport.md)
- [Project Estimation](docs\Estimation.md)


## Test Coverage

![App Screenshot](images\coverage.png)

## License

[AGPL License](https://www.gnu.org/licenses/agpl-3.0)

