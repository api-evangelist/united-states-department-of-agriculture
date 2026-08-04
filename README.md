# United States Department of Agriculture (united-states-department-of-agriculture)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
