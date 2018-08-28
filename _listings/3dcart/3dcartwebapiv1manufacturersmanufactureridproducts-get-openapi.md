---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get all products from a specific manufacturer
  version: 1.0.0
  description: Get all products from a specific manufacturer.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Manufacturers:
    get:
      summary: Get all Manufacturers
      description: Get all manufacturers.
      operationId: Manufacturer_GetAllManufacturers
      x-api-path-slug: 3dcartwebapiv1manufacturers-get
      parameters:
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: manufacturer
        description: Name of the Manufacturer
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Manufacturers
    put:
      summary: This method is used to update multiple manufacturers in the database.
        No URL parameters should be included.
      description: This method is used to update multiple manufacturers in the database.
        no url parameters should be included..
      operationId: Manufacturer_Update
      x-api-path-slug: 3dcartwebapiv1manufacturers-put
      parameters:
      - in: body
        name: manufacturers
        description: A Json or XML object containing the new manufacturers
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Multiple
      - Manufacturers
      - In
      - Database
      - ""
      - "No"
      - URL
      - Parameters
      - Should
      - Be
      - Included
    post:
      summary: Adds a new manufacturer to the system
      description: Adds a new manufacturer to the system.
      operationId: Manufacturer_Post
      x-api-path-slug: 3dcartwebapiv1manufacturers-post
      parameters:
      - in: body
        name: manufacturer
        description: A Json or XML object containing the new manufacturer
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Manufacturer
      - To
      - System
  /3dCartWebAPI/v1/Manufacturers/{id}:
    get:
      summary: Get a Manufacturer
      description: Get a manufacturer.
      operationId: Manufacturer_GetManufacturer
      x-api-path-slug: 3dcartwebapiv1manufacturersid-get
      parameters:
      - in: path
        name: id
        description: Manufacturer ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Manufacturer
    delete:
      summary: Deletes a Manufacturer in the system
      description: Deletes a manufacturer in the system.
      operationId: Manufacturer_Delete
      x-api-path-slug: 3dcartwebapiv1manufacturersid-delete
      parameters:
      - in: path
        name: id
        description: Manufacturer ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Manufacturer
      - In
      - System
  /3dCartWebAPI/v1/Manufacturers/{manufacturerid}:
    put:
      summary: This method is used to update a single manufacturer record in the database.
        The {manufacturerid} parameter specifies which manufacturer record to update.
      description: This method is used to update a single manufacturer record in the
        database. the {manufacturerid} parameter specifies which manufacturer record
        to update..
      operationId: Manufacturer_Update
      x-api-path-slug: 3dcartwebapiv1manufacturersmanufacturerid-put
      parameters:
      - in: body
        name: manufacturer
        description: A Json or XML object containing the new manufacturer
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: manufacturerid
        description: Manufacturer ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Manufacturer
      - Record
      - In
      - Database
      - ""
      - Manufacturerid
      - Parameter
      - Specifies
      - Which
      - Manufacturer
      - Record
      - To
      - Update
  /3dCartWebAPI/v1/Manufacturers/{manufacturerid}/Products:
    get:
      summary: Get all products from a specific manufacturer
      description: Get all products from a specific manufacturer.
      operationId: Products_GetAllProductsFromManufacturer
      x-api-path-slug: 3dcartwebapiv1manufacturersmanufactureridproducts-get
      parameters:
      - in: query
        name: categoryspecial
        description: Category Special Flag
      - in: query
        name: costfrom
        description: Cost of a product
      - in: query
        name: costto
        description: Cost of a product
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: freeshipping
        description: Free Shipping Flag
      - in: query
        name: giftcertificate
        description: Gift Certificate Flag
      - in: query
        name: hide
        description: Hide Flag
      - in: query
        name: homespecial
        description: Home Special Flag
      - in: query
        name: lastupdateend
        description: End Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastupdatestart
        description: Start Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: path
        name: manufacturerid
        description: ID of the manufacturer
      - in: query
        name: name
        description: Name of the product
      - in: query
        name: nonsearchable
        description: Non-Searchable Flag
      - in: query
        name: nontax
        description: Non-Taxable Flag
      - in: query
        name: notforsale
        description: Not For Sale Flag
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: onsale
        description: On Sale Flag
      - in: query
        name: pricefrom
        description: Price of a product
      - in: query
        name: priceto
        description: Price of a product
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: query
        name: rewarddisable
        description: Disable Rewards Flag
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: selfship
        description: Ships by itself Flag
      - in: query
        name: sku
        description: SKU Code of the product
      - in: query
        name: stockfrom
        description: Stock of a product
      - in: query
        name: stockto
        description: Stock of a product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
      - From
      - Specific
      - Manufacturer
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---