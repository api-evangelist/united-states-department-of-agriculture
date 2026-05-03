# United States Department of Agriculture

The United States Department of Agriculture (USDA) is a federal agency responsible for developing and executing policies related to farming, agriculture, forestry, and food. The USDA works to ensure the sustainability and safety of America's food supply, while also supporting rural development and promoting economic growth in rural communities. The agency provides farmers and ranchers with financial assistance, technical support, and resources to help them improve operations and increase productivity.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
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
- **Modified:** 2026-05-03

---

## APIs

### USDA FoodData Central API

The FoodData Central API provides REST access to FoodData Central (FDC), the USDA's integrated data system providing expanded nutrient profiles linked to agricultural research. Covers Foundation Foods, SR Legacy, Branded Foods, FNDDS, and Experimental Foods.

**Human URL:** https://fdc.nal.usda.gov/api-guide/

#### Tags

- Food, Nutrition, Agriculture, Federal Government

#### Properties

- [Documentation](https://fdc.nal.usda.gov/api-guide/)
- [OpenAPI](openapi/usda-fooddata-central-openapi.yml)
- [SpectralRules](rules/usda-fooddata-central-rules.yml)
- [NaftikoCapability](capabilities/food-data-research.yaml)
- [SignUp](https://fdc.nal.usda.gov/api-key-signup/)

---

### USDA NASS Quick Stats API

Provides direct access to USDA NASS official published aggregate estimates for U.S. agricultural production. Returns crop, livestock, economics, and demographic data by commodity, geography, and year.

**Human URL:** https://quickstats.nass.usda.gov/api

#### Tags

- Agriculture, Statistics, Crops, Livestock, Federal Government

#### Properties

- [Documentation](https://quickstats.nass.usda.gov/api)
- [Portal](https://www.nass.usda.gov/developer/index.php)
- [OpenAPI](openapi/usda-nass-quickstats-openapi.yml)
- [NaftikoCapability](capabilities/food-data-research.yaml)

---

### USDA ERS ARMS Data API

Provides access to USDA Economic Research Service Agricultural Resource Management Survey data covering farm finances, production practices, and resource use for U.S. farms.

**Human URL:** https://www.ers.usda.gov/developer/data-apis/arms-data-api

#### Tags

- Agriculture, Economics, Farm Management, Federal Government

#### Properties

- [Documentation](https://www.ers.usda.gov/developer/data-apis/arms-data-api)
- [Portal](https://www.ers.usda.gov/developer/)
- [OpenAPI](openapi/usda-ers-arms-openapi.yml)

---

### USDA NRCS AWDB Water and Climate REST API

REST API for SNOTEL, SCAN, and other monitoring station data including snow water equivalent, precipitation, temperature, and soil moisture for water supply forecasting.

**Human URL:** https://wcc.sc.egov.usda.gov/awdbRestApi/swagger-ui/index.html

#### Tags

- Water, Climate, Snow, SNOTEL, Federal Government

#### Properties

- [SwaggerUI](https://wcc.sc.egov.usda.gov/awdbRestApi/swagger-ui/index.html)
- [Documentation](https://www.nrcs.usda.gov/sites/default/files/2023-03/AWDB%20Web%20Service%20User%20Guide.pdf)
- [OpenAPI](openapi/usda-nrcs-awdb-openapi.yml)

---

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [usda-fooddata-central-openapi.yml](openapi/usda-fooddata-central-openapi.yml) | FoodData Central food search and nutrient data API |
| [usda-nass-quickstats-openapi.yml](openapi/usda-nass-quickstats-openapi.yml) | NASS Quick Stats agricultural production statistics API |
| [usda-ers-arms-openapi.yml](openapi/usda-ers-arms-openapi.yml) | ERS ARMS farm survey data API |
| [usda-nrcs-awdb-openapi.yml](openapi/usda-nrcs-awdb-openapi.yml) | NRCS AWDB water and climate monitoring REST API |

### Spectral Rules

| File | Description |
|------|-------------|
| [usda-fooddata-central-rules.yml](rules/usda-fooddata-central-rules.yml) | Spectral lint rules for USDA FoodData Central API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | APIs |
|------|------|
| [shared/usda-fooddata-central.yaml](capabilities/shared/usda-fooddata-central.yaml) | USDA FoodData Central (3 operations) |
| [shared/usda-nass-quickstats.yaml](capabilities/shared/usda-nass-quickstats.yaml) | USDA NASS Quick Stats (3 operations) |

#### Workflow Capabilities

| File | Description | Tools |
|------|-------------|-------|
| [food-data-research.yaml](capabilities/food-data-research.yaml) | Food nutrition and agricultural data research workflows | 6 tools |

### JSON Schemas

| File | Description |
|------|-------------|
| [usda-fdc-food-item-schema.json](json-schema/usda-fdc-food-item-schema.json) | Schema for USDA FoodData Central food item records |
| [usda-nass-stat-record-schema.json](json-schema/usda-nass-stat-record-schema.json) | Schema for USDA NASS agricultural statistics records |

### JSON Structures

| File | Description |
|------|-------------|
| [usda-fdc-food-item-structure.json](json-structure/usda-fdc-food-item-structure.json) | Field structure for FoodData Central food items |

### JSON-LD Context

| File | Description |
|------|-------------|
| [united-states-department-of-agriculture-context.jsonld](json-ld/united-states-department-of-agriculture-context.jsonld) | Linked data context mapping USDA food and agriculture vocabulary |

### Examples

| File | Operation |
|------|-----------|
| [usda-fdc-search-foods-example.json](examples/usda-fdc-search-foods-example.json) | Search Foods (FoodData Central) |
| [usda-nass-get-statistics-example.json](examples/usda-nass-get-statistics-example.json) | Get Agricultural Statistics (NASS Quick Stats) |
| [usda-awdb-get-station-data-example.json](examples/usda-awdb-get-station-data-example.json) | Get Station Data (AWDB REST API) |

### Vocabulary

| File | Description |
|------|-------------|
| [united-states-department-of-agriculture-vocabulary.yml](vocabulary/united-states-department-of-agriculture-vocabulary.yml) | USDA domain vocabulary (ARMS, FDC, NASS, SNOTEL, SCAN, etc.) |

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
