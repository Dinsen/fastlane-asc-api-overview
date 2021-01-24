
### App Store Connect API v1.2 implementation overview

| Module | Implemented | Type | Endpoint |
| ------ | ------ | ------ | ------ |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/ageRatingDeclaration |
| Tunes | X | PATCH | apps/#{app_id} |
| Tunes | X | GET | apps/#{app_id}/dataUsages |
| Tunes | X | GET | appPreviews/#{app_preview_id} |
| Tunes | X | POST | appPreviews |
| Tunes | X | PATCH | appPreviews/#{app_preview_id} |
| Tunes | X | DELETE | appPreviews/#{app_preview_id} |
| Tunes | X | GET | appPreviewSets |
| Tunes | X | GET | appPreviewSets/#{app_preview_set_id} |
| Tunes | X | POST | appPreviewSets |
| Tunes | X | PATCH | appPreviewSets/#{app_preview_set_id}/relationships/appPreviews |
| Tunes | X | GET | apps/#{app_id}/availableTerritories |
| Tunes | X | GET | appPrices |
| Tunes | X | GET | appPrices/#{app_price_id} |
| Tunes | X | GET | appPricePoints |
| Tunes | X | POST | appStoreReviewAttachments |
| Tunes | X | PATCH | appStoreReviewAttachments/#{app_store_review_attachment_id} |
| Tunes | X | DELETE | appStoreReviewAttachments/#{app_store_review_attachment_id} |
| Tunes | X | GET | appStoreVersionLocalizations/#{app_store_version_localization_id}/appScreenshotSets |
| Tunes | X | GET | appScreenshotSets/#{app_screenshot_set_id} |
| Tunes | X | POST | appScreenshotSets |
| Tunes | X | PATCH | appScreenshotSets/#{app_screenshot_set_id}/relationships/appScreenshots |
| Tunes | X | GET | appScreenshots/#{app_screenshot_id} |
| Tunes | X | POST | appScreenshots |
| Tunes | X | PATCH | appScreenshots/#{app_screenshot_id} |
| Tunes | X | DELETE | appScreenshots/#{app_screenshot_id} |
| Tunes | X | GET | apps/#{app_id}/appInfos |
| Tunes | X | PATCH | appInfos/#{app_info_id} |
| Tunes | X | PATCH | appInfos/#{app_info_id} |
| Tunes | X | DELETE | appInfos/#{app_info_id} |
| Tunes | X | GET | appInfos/#{app_info_id}/appInfoLocalizations |
| Tunes | X | POST | appInfoLocalizations |
| Tunes | X | PATCH | appInfoLocalizations/#{app_info_localization_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/appStoreReviewDetail |
| Tunes | X | POST | appStoreReviewDetails |
| Tunes | X | PATCH | appStoreReviewDetails/#{app_store_review_detail_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/appStoreVersionLocalizations |
| Tunes | X | POST | appStoreVersionLocalizations |
| Tunes | X | PATCH | appStoreVersionLocalizations/#{app_store_version_localization_id} |
| Tunes | X | DELETE | appStoreVersionLocalizations/#{app_store_version_localization_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/appStoreVersionPhasedRelease |
| Tunes | X | POST | appStoreVersionPhasedReleases |
| Tunes | X | PATCH | appStoreVersionPhasedReleases/#{app_store_version_phased_release_id} |
| Tunes | X | DELETE | appStoreVersionPhasedReleases/#{app_store_version_phased_release_id} |
| Tunes | X | GET | apps/#{app_id}/appStoreVersions |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id} |
| Tunes | X | POST | appStoreVersions |
| Tunes | X | PATCH | appStoreVersions/#{app_store_version_id} |
| Tunes | X | PATCH | appStoreVersions/#{app_store_version_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/resetRatingsRequest |
| Tunes | X | POST | resetRatingsRequests |
| Tunes | X | DELETE | resetRatingsRequests/#{reset_ratings_request_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/appStoreVersionSubmission |
| Tunes | X | POST | appStoreVersionSubmissions |
| Tunes | X | DELETE | appStoreVersionSubmissions/#{app_store_version_submission_id} |
| Tunes | X | POST | appStoreVersionReleaseRequests |
| Tunes | X | GET | apps/#{app_id}/customAppUsers |
| Tunes | X | POST | customAppUsers |
| Tunes | X | DELETE | customAppUsers/#{custom_app_user_id} |
| Tunes | X | GET | apps/#{app_id}/customAppOrganizations |
| Tunes | X | POST | customAppOrganizations |
| Tunes | X | DELETE | customAppOrganizations/#{custom_app_organization_id} |
| Tunes | X | GET | appStoreVersions/#{app_store_version_id}/idfaDeclaration |
| Tunes | X | POST | idfaDeclarations |
| Tunes | X | PATCH | idfaDeclarations/#{idfa_declaration_id} |
| Tunes | X | DELETE | idfaDeclarations/#{idfa_declaration_id} |
| Tunes | X | GET | sandboxTesters |
| Tunes | X | POST | sandboxTesters |
| Tunes | X | DELETE | sandboxTesters/#{sandbox_tester_id} |
| Tunes | X | GET | territories |


<details><summary>AgeRatingDeclarations</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | PATCH  | ageRatingDeclarations/#{age_rating_declaration_id} |
</details>

<details><summary>AppCategories</summary>

| Module   | Added | Type   | Endpoint                         |
| -------- | :---: | ------ | -------------------------------- |
| Tunes    | ❌    | GET    | appCategories                    |
| Tunes    | ❌    | GET    | appCategories/{id}               |
| Tunes    | ❌    | GET    | appCategories/{id}/parent        |
| Tunes    | ❌    | GET    | appCategories/{id}/subcategories |
</details>

<details><summary>AppEncryptionDeclarations</summary>

| Module   | Added | Type   | Endpoint                                            |
| -------- | :---: | ------ | --------------------------------------------------- |
| Tunes    | ❌    | GET    | appEncryptionDeclarations                           |
| Tunes    | ❌    | GET    | appEncryptionDeclarations/{id}                      |
| Tunes    | ❌    | GET    | appEncryptionDeclarations/{id}/app                  |
| Tunes    | ❌    | POST   | appEncryptionDeclarations/{id}/relationships/builds |
</details>

<details><summary>AppInfoLocalizations</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | POST   | appInfoLocalizations |
| Tunes    | ✅    | GET    | appInfoLocalizations/{id} |
| Tunes    | ✅    | PATCH  | appInfoLocalizations/{id} |
| Tunes    | ✅    | DELETE | appInfoLocalizations/{id} |
</details>

<details><summary>AppInfos</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    | appInfos/{id} |
| Tunes    | ✅    | PATCH  | appInfos/{id} |
| Tunes    | ✅    | GET    | appInfos/{id}/appInfoLocalizations |
| Tunes    | ✅    | GET    | appInfos/{id}/primaryCategory |
| Tunes    | ✅    | GET    | appInfos/{id}/primarySubcategoryOne |
| Tunes    | ✅    | GET    | appInfos/{id}/primarySubcategoryTwo |
| Tunes    | ✅    | GET    | appInfos/{id}/secondaryCategory |
| Tunes    | ✅    | GET    | appInfos/{id}/secondarySubcategoryOne |
| Tunes    | ✅    | GET    | appInfos/{id}/secondarySubcategoryTwo |
</details>

<details><summary>AppPreOrders</summary>

| Module   | Added | Type   | Endpoint          |
| -------- | :---: | ------ | ----------------- |
| Tunes    | ❌    | POST   | appPreOrders      |
| Tunes    | ❌    | GET    | appPreOrders/{id} |
| Tunes    | ❌    | PATCH  | appPreOrders/{id} |
| Tunes    | ❌    | DELETE | appPreOrders/{id} |
</details>

<details><summary>AppPreviewSets</summary>

| Module   | Added | Type   | Endpoint                                      |
| -------- | :---: | ------ | --------------------------------------------- |
| Tunes    | ✅    | POST   | appPreviewSets                                |
| Tunes    | ✅    | GET    | appPreviewSets/{id}                           |
| Tunes    | ✅    | DELETE | appPreviewSets/{id}                           |
| Tunes    | ✅    | GET    | appPreviewSets/{id}/relationships/appPreviews |
| Tunes    | ✅    | PATCH  | appPreviewSets/{id}/relationships/appPreviews |
| Tunes    | ✅    | GET    | appPreviewSets/{id}/appPreviews               |
</details>

<details><summary>AppPreviews</summary>

| Module   | Added | Type   | Endpoint         |
| -------- | :---: | ------ | ---------------- |
| Tunes    | ✅    | POST   | appPreviews      |
| Tunes    | ✅    | GET    | appPreviews/{id} |
| Tunes    | ✅    | PATCH  | appPreviews/{id} |
| Tunes    | ✅    | DELETE | appPreviews/{id} |
</details>

<details><summary>AppPricePoints</summary>

| Module   | Added | Type   | Endpoint                      |
| -------- | :---: | ------ | ----------------------------- |
| Tunes    | ✅    | GET    | appPricePoints                |
| Tunes    | ❌    | GET    | appPricePoints/{id}           |
| Tunes    | ❌    | GET    | appPricePoints/{id}/territory |
</details>

<details><summary>AppPriceTiers</summary>

| Module   | Added | Type   | Endpoint                       |
| -------- | :---: | ------ | ------------------------------ |
| Tunes    | ✅    | GET    | appPriceTiers                  |
| Tunes    | ✅    | GET    | appPriceTiers/{id}             |
| Tunes    | ✅    | GET    | appPriceTiers/{id}/pricePoints |
</details>

<details><summary>AppPrices</summary>

| Module   | Added | Type   | Endpoint           |
| -------- | :---: | ------ | ------------------ |
| Tunes    | ✅    | GET    | /v1/appPrices/{id} |
</details>

<details><summary>AppScreenshotSets</summary>

| Module   | Added | Type   | Endpoint                                            |
| -------- | :---: | ------ | --------------------------------------------------- |
| Tunes    | ✅    | POST   | appScreenshotSets                                   |
| Tunes    | ✅    | GET    | appScreenshotSets/{id}                              |
| Tunes    | ✅    | DELETE | appScreenshotSets/{id}                              |
| Tunes    | ✅    | GET    | appScreenshotSets/{id}/relationships/appScreenshots |
| Tunes    | ✅    | PATCH  | appScreenshotSets/{id}/relationships/appScreenshots |
| Tunes    | ✅    | GET    | appScreenshotSets/{id}/appScreenshots               |
</details>

<details><summary>AppScreenshots</summary>

| Module   | Added | Type   | Endpoint            |
| -------- | :---: | ------ | ------------------- |
| Tunes    | ✅    | POST   | appScreenshots      |
| Tunes    | ✅    | GET    | appScreenshots/{id} |
| Tunes    | ✅    | PATCH  | appScreenshots/{id} |
| Tunes    | ✅    | DELETE | appScreenshots/{id} |
</details>

<details><summary>AppStoreReviewAttachments</summary>

| Module   | Added | Type   | Endpoint                       |
| -------- | :---: | ------ | ------------------------------ |
| Tunes    | ✅    | POST   | appStoreReviewAttachments      |
| Tunes    | ✅    | GET    | appStoreReviewAttachments/{id} |
| Tunes    | ✅    | PATCH  | appStoreReviewAttachments/{id} |
| Tunes    | ✅    | DELETE | appStoreReviewAttachments/{id} |
</details>

<details><summary>AppStoreReviewDetails</summary>

| Module   | Added | Type   | Endpoint                                             |
| -------- | :---: | ------ | ---------------------------------------------------- |
| Tunes    | ✅    | POST   | appStoreReviewDetails                                |
| Tunes    | ✅    | GET    | appStoreReviewDetails/{id}                           |
| Tunes    | ✅    | PATCH  | appStoreReviewDetails/{id}                           |
| Tunes    | ✅    | GET    | appStoreReviewDetails/{id}/appStoreReviewAttachments |
</details>

<details><summary>AppStoreVersionLocalizations</summary>

| Module   | Added | Type   | Endpoint                                            |
| -------- | :---: | ------ | --------------------------------------------------- |
| Tunes    | ✅    | POST   | appStoreVersionLocalizations                        |
| Tunes    | ✅    | GET    | appStoreVersionLocalizations/{id}                   |
| Tunes    | ✅    | PATCH  | appStoreVersionLocalizations/{id}                   |
| Tunes    | ✅    | DELETE | appStoreVersionLocalizations/{id}                   |
| Tunes    | ✅    | GET    | appStoreVersionLocalizations/{id}/appPreviewSets    |
| Tunes    | ✅    | GET    | appStoreVersionLocalizations/{id}/appScreenshotSets |
</details>

<details><summary>AppStoreVersionPhasedReleases</summary>

| Module   | Added | Type   | Endpoint                           |
| -------- | :---: | ------ | ---------------------------------- |
| Tunes    | ✅    | POST   | appStoreVersionPhasedReleases      |
| Tunes    | ✅    | PATCH  | appStoreVersionPhasedReleases/{id} |
| Tunes    | ✅    | DELETE | appStoreVersionPhasedReleases/{id} |
</details>
<details>
<summary>AppStoreVersionSubmissions</summary>

| Module   | Added | Type   | Endpoint                        |
| -------- | :---: | ------ | ------------------------------- |
| Tunes    | ✅    | POST   | appStoreVersionSubmissions      |
| Tunes    | ✅    | DELETE | appStoreVersionSubmissions/{id} |
</details>

<details><summary>AppStoreVersions</summary>

| Module   | Added | Type   | Endpoint                                           |
| -------- | :---: | ------ | -------------------------------------------------- |
| Tunes    | ✅    | POST   | appStoreVersions                                   |
| Tunes    | ✅    | GET    | appStoreVersions/{id}                              |
| Tunes    | ✅    | PATCH  | appStoreVersions/{id}                              |
| Tunes    | ✅    | DELETE | appStoreVersions/{id}                              |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/ageRatingDeclaration         |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/appStoreReviewDetail         |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/appStoreVersionLocalizations |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/appStoreVersionPhasedRelease |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/appStoreVersionSubmission    |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/relationships/build          |
| Tunes    | ✅    | PATCH  | appStoreVersions/{id}/relationships/build          |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/build                        |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/idfaDeclaration              |
| Tunes    | ✅    | GET    | appStoreVersions/{id}/routingAppCoverage           |
</details>

<details><summary>Apps</summary>

| Module   | Added | Type   | Endpoint                                |
| -------- | :---: | ------ | --------------------------------------- |
| Tunes    | ✅    | GET    | /v1/apps                                |
| Tunes    | ✅    | GET    | /v1/apps/{id}                           |
| Tunes    | ✅    | PATCH  | /v1/apps/{id}                           |
| Tunes    | ✅    | GET    | /v1/apps/{id}/appInfos                  |
| Tunes    | ✅    | GET    | /v1/apps/{id}/appStoreVersions          |
| Tunes    | ✅    | GET    | /v1/apps/{id}/availableTerritories      |
| Tunes    | ✅    | GET    | /v1/apps/{id}/betaAppLocalizations      |
| Tunes    | ✅    | GET    | /v1/apps/{id}/betaAppReviewDetail       |
| Tunes    | ✅    | GET    | /v1/apps/{id}/betaGroups                |
| Tunes    | ✅    | GET    | /v1/apps/{id}/betaLicenseAgreement      |
| Tunes    | ✅    | DELETE | /v1/apps/{id}/relationships/betaTesters |
| Tunes    | ✅    | GET    | /v1/apps/{id}/builds                    |
| Tunes    | ✅    | GET    | /v1/apps/{id}/endUserLicenseAgreement   |
| Tunes    | ✅    | GET    | /v1/apps/{id}/gameCenterEnabledVersions |
| Tunes    | ✅    | GET    | /v1/apps/{id}/inAppPurchases            |
| Tunes    | ✅    | GET    | /v1/apps/{id}/perfPowerMetrics          |
| Tunes    | ✅    | GET    | /v1/apps/{id}/preOrder                  |
| Tunes    | ✅    | GET    | /v1/apps/{id}/preReleaseVersions        |
| Tunes    | ✅    | GET    | /v1/apps/{id}/prices                    |
</details>

<details><summary>BetaAppLocalizations</summary>

| Module     | Added | Type   | Endpoint                      |
| ---------- | :---: | ------ | ----------------------------- |
| TestFlight | ✅    | GET    | betaAppLocalizations          |
| TestFlight | ✅    | POST   | betaAppLocalizations          |
| TestFlight | ✅    | GET    | betaAppLocalizations/{id}     |
| TestFlight | ✅    | PATCH  | betaAppLocalizations/{id}     |
| TestFlight | ✅    | DELETE | betaAppLocalizations/{id}     |
| TestFlight | ✅    | GET    | betaAppLocalizations/{id}/app |
</details>

<details><summary>BetaAppReviewDetails</summary>

| Module     | Added | Type   | Endpoint                          |
| ---------- | :---: | ------ | --------------------------------- |
| TestFlight | ✅    | GET    | /v1/betaAppReviewDetails          |
| TestFlight | ✅    | GET    | /v1/betaAppReviewDetails/{id}     |
| TestFlight | ✅    | PATCH  | /v1/betaAppReviewDetails/{id}     |
| TestFlight | ✅    | GET    | /v1/betaAppReviewDetails/{id}/app |
</details>

<details><summary>BetaAppReviewSubmissions</summary>

| Module     | Added | Type   | Endpoint                            |
| ---------- | :---: | ------ | ----------------------------------- |
| TestFlight | ✅    | GET    | betaAppReviewSubmissions            |
| TestFlight | ✅    | POST   | betaAppReviewSubmissions            |
| TestFlight | ✅    | GET    | betaAppReviewSubmissions/{id}       |
| TestFlight | ✅    | GET    | betaAppReviewSubmissions/{id}/build |
</details>

<details><summary>BetaBuildLocalizations</summary>

| Module     | Added | Type   | Endpoint                          |
| ---------- | :---: | ------ | --------------------------------- |
| TestFlight | ✅    | GET    | betaBuildLocalizations            |
| TestFlight | ✅    | POST   | betaBuildLocalizations            |
| TestFlight | ✅    | GET    | betaBuildLocalizations/{id}       |
| TestFlight | ✅    | PATCH  | betaBuildLocalizations/{id}       |
| TestFlight | ✅    | DELETE | betaBuildLocalizations/{id}       |
| TestFlight | ✅    | GET    | betaBuildLocalizations/{id}/build |
</details>

<details><summary>BetaGroups</summary>

| Module     | Added | Type   | Endpoint                                      |
| ---------- | :---: | ------ | --------------------------------------------- |
| TestFlight | ✅    | GET    | /v1/betaGroups                                |
| TestFlight | ✅    | POST   | /v1/betaGroups                                |
| TestFlight | ✅    | GET    | /v1/betaGroups/{id}                           |
| TestFlight | ✅    | PATCH  | /v1/betaGroups/{id}                           |
| TestFlight | ✅    | DELETE | /v1/betaGroups/{id}                           |
| TestFlight | ✅    | GET    | /v1/betaGroups/{id}/app                       |
| TestFlight | ✅    | GET    | /v1/betaGroups/{id}/relationships/betaTesters |
| TestFlight | ✅    | POST   | /v1/betaGroups/{id}/relationships/betaTesters |
| TestFlight | ✅    | DELETE | /v1/betaGroups/{id}/relationships/betaTesters |
| TestFlight | ✅    | GET    | /v1/betaGroups/{id}/betaTesters               |
| TestFlight | ✅    | GET    | /v1/betaGroups/{id}/relationships/builds      |
| TestFlight | ✅    | POST   | /v1/betaGroups/{id}/relationships/builds      |
| TestFlight | ✅    | DELETE | /v1/betaGroups/{id}/relationships/builds      |
| TestFlight | ✅    | GET    | /v1/betaGroups/{id}/builds                    |
</details>

<details><summary>BetaLicenseAgreements</summary>

| Module     | Added | Type   | Endpoint                       |
| ---------- | :---: | ------ | ------------------------------ |
| TestFlight | ✅    | GET    | betaLicenseAgreements          |
| TestFlight | ✅    | GET    | betaLicenseAgreements/{id}     |
| TestFlight | ✅    | PATCH  | betaLicenseAgreements/{id}     |
| TestFlight | ✅    | GET    | betaLicenseAgreements/{id}/app |
</details>

<details><summary>BetaTesterInvitations</summary>

| Module     | Added | Type   | Endpoint |
| ---------- | :---: | ------ | -------- |
| TestFlight | ✅    | POST   | /v1/betaTesterInvitations |
</details>

<details><summary>BetaTesters</summary>

| Module     | Added | Type   | Endpoint                                  |
| ---------- | :---: | ------ | ----------------------------------------- |
| TestFlight | ✅    | GET    | betaTesters                               |
| TestFlight | ✅    | POST   | betaTesters                               |
| TestFlight | ✅    | GET    | betaTesters/{id}                          |
| TestFlight | ✅    | DELETE | betaTesters/{id}                          |
| TestFlight | ✅    | GET    | betaTesters/{id}/relationships/apps       |
| TestFlight | ✅    | DELETE | betaTesters/{id}/relationships/apps       |
| TestFlight | ✅    | GET    | betaTesters/{id}/apps                     |
| TestFlight | ✅    | GET    | betaTesters/{id}/relationships/betaGroups |
| TestFlight | ✅    | PATCH  | betaTesters/{id}/relationships/betaGroups |
| TestFlight | ✅    | DELETE | betaTesters/{id}/relationships/betaGroups |
| TestFlight | ✅    | GET    | betaTesters/{id}/betaGroups               |
| TestFlight | ✅    | GET    | betaTesters/{id}/relationships/builds     |
| TestFlight | ✅    | PATCH  | betaTesters/{id}/relationships/builds     |
| TestFlight | ✅    | DELETE | betaTesters/{id}/relationships/builds     |
| TestFlight | ✅    | GET    | betaTesters/{id}/builds                   |
</details>

<details><summary>BuildBetaDetails</summary>

| Module     | Added | Type   | Endpoint                    |
| ---------- | :---: | ------ | --------------------------- |
| TestFlight | ✅    | GET    | buildBetaDetails            |
| TestFlight | ✅    | GET    | buildBetaDetails/{id}       |
| TestFlight | ✅    | PATCH  | buildBetaDetails/{id}       |
| TestFlight | ✅    | GET    | buildBetaDetails/{id}/build |
</details>

<details><summary>BuildBetaNotifications</summary>

| Module     | Added | Type   | Endpoint |
| ---------- | :---: | ------ | -------- |
| TestFlight | ✅    | GET    |          |
</details>

<details><summary>Builds</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>BundleIdCapabilities</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>BundleIds</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>Certificates</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>Devices</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>EndUserLicenseAgreements</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>FinanceReports</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>IdfaDeclarations</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>InAppPurchases</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>PreReleaseVersions</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>Profiles</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>RoutingAppCoverages</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>SalesReports</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>Territories</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>UserInvitations</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Users    | ✅    | GET    |  |
</details>

<details><summary>Users</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Users    | ✅    | GET    |  |
</details>

<details><summary>DiagnosticSignatures</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

<details><summary>GameCenterEnabledVersions</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    |  |
</details>

