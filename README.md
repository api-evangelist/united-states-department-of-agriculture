# United States Department of Agriculture (united-states-department-of-agriculture)

The United States Department of Agriculture (USDA) is a federal agency responsible for developing and executing policies related to farming, agriculture, forestry, and food. The USDA works to ensure the sustainability and safety of America's food supply, while also supporting rural development and promoting economic growth in rural communities. USDA provides multiple public APIs including FoodData Central for nutrient data, NASS Quick Stats for agricultural statistics, ERS ARMS for farm economics, and NRCS AWDB for water and climate monitoring data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Agriculture
- Food Safety
- Nutrition
- Rural Development
- Climate

## Timestamps

- **Created:** 2024-11-14
- **Modified:** 2026-05-19

## APIs

### USDA FoodData Central API

The FoodData Central API provides REST access to FoodData Central (FDC), the USDA's integrated data system that provides expanded nutrient profile data and links to related agricultural and experimental research. The API supports food search, nutrient lookup, and retrieval of food details across multiple food data types including Foundation Foods, SR Legacy, FNDDS, Branded Foods, and Experimental Foods.

- **Human URL:** [https://fdc.nal.usda.gov/api-guide/](https://fdc.nal.usda.gov/api-guide/)
- **Base URL:** `https://api.nal.usda.gov/fdc/v1`

#### Tags

- Food
- Nutrition
- Agriculture
- Federal Government

#### Properties

- [Documentation](https://fdc.nal.usda.gov/api-guide/)
- [OpenAPI](https://api.nal.usda.gov/fdc/v1/yaml-spec?api_key=DEMO_KEY) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-fooddata-central-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/rules/usda-fooddata-central-rules.yml)
- [Sign Up](https://fdc.nal.usda.gov/api-key-signup/)
- [Postman Collection](collections/usda-ers-arms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-ers-arms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-fooddata-central.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-fooddata-central.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-nass-quickstats.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-nass-quickstats.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-nrcs-awdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-nrcs-awdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USDA NASS Quick Stats API

The USDA NASS Quick Stats API provides direct access to the National Agricultural Statistics Service's official published aggregate estimates related to U.S. agricultural production. Returns data for commodities, categories, and geographic areas, supporting queries on crops, livestock, economics, and demographics with responses in JSON, CSV, or XML formats.

- **Human URL:** [https://quickstats.nass.usda.gov/api](https://quickstats.nass.usda.gov/api)
- **Base URL:** `https://quickstats.nass.usda.gov/api`

#### Tags

- Agriculture
- Statistics
- Crops
- Livestock
- Federal Government

#### Properties

- [Documentation](https://quickstats.nass.usda.gov/api)
- [Portal](https://www.nass.usda.gov/developer/index.php)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-nass-quickstats-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usda-ers-arms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-ers-arms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-fooddata-central.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-fooddata-central.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-nass-quickstats.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-nass-quickstats.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-nrcs-awdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-nrcs-awdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USDA ERS ARMS Data API

The USDA Economic Research Service (ERS) ARMS Data API provides access to the Agricultural Resource Management Survey (ARMS), covering farm finances, production practices, and resource use for U.S. farms. Supports attribute- based querying of farm income, balance sheet, costs, and production data by year, state, and report type.

- **Human URL:** [https://www.ers.usda.gov/developer/data-apis/arms-data-api](https://www.ers.usda.gov/developer/data-apis/arms-data-api)
- **Base URL:** `https://api.ers.usda.gov/data/arms`

#### Tags

- Agriculture
- Economics
- Farm Management
- Federal Government

#### Properties

- [Documentation](https://www.ers.usda.gov/developer/data-apis/arms-data-api)
- [Portal](https://www.ers.usda.gov/developer/data-apis/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-ers-arms-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usda-ers-arms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-ers-arms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-fooddata-central.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-fooddata-central.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-nass-quickstats.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-nass-quickstats.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-nrcs-awdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-nrcs-awdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USDA NRCS AWDB Water and Climate REST API

The USDA Natural Resources Conservation Service (NRCS) Air and Water Database (AWDB) REST API provides access to snow, water, and climate data from SNOTEL (SNOw TELemetry) stations and Soil Climate Analysis Network (SCAN) stations. Supports retrieval of daily, monthly, and annual hydrology and climate data for water resource management.

- **Human URL:** [https://wcc.sc.egov.usda.gov/awdbRestApi/swagger-ui/index.html](https://wcc.sc.egov.usda.gov/awdbRestApi/swagger-ui/index.html)
- **Base URL:** `https://wcc.sc.egov.usda.gov/awdbRestApi/services/v1`

#### Tags

- Water
- Climate
- Snow
- SNOTEL
- Federal Government

#### Properties

- [Swagger U I](https://wcc.sc.egov.usda.gov/awdbRestApi/swagger-ui/index.html)
- [Documentation](https://www.nrcs.usda.gov/sites/default/files/2023-03/AWDB%20Web%20Service%20User%20Guide.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-nrcs-awdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usda-ers-arms.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-ers-arms.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-fooddata-central.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-fooddata-central.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-nass-quickstats.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-nass-quickstats.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usda-nrcs-awdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usda-nrcs-awdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/usda)
- [LinkedIn](https://www.linkedin.com/company/usda)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
