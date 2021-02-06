
### App Store Connect API v1.2 implementation overview

| Module | Implemented | Type | Endpoint |
| ------ | ------ | ------ | ------ |
| Tunes |   | GET | apps/#{app_id}/dataUsages |
| Tunes | X | DELETE | appInfos/#{app_info_id} |
| Tunes | ? | GET | appStoreVersions/#{app_store_version_id}/resetRatingsRequest |
| Tunes | ? | POST | resetRatingsRequests |
| Tunes | ? | DELETE | resetRatingsRequests/#{reset_ratings_request_id} |
| Tunes | ? | POST | appStoreVersionReleaseRequests |
| Tunes | ? | GET | apps/#{app_id}/customAppUsers |
| Tunes | ? | POST | customAppUsers |
| Tunes | ? | DELETE | customAppUsers/#{custom_app_user_id} |
| Tunes | ? | GET | apps/#{app_id}/customAppOrganizations |
| Tunes | ? | POST | customAppOrganizations |
| Tunes | ? | DELETE | customAppOrganizations/#{custom_app_organization_id} |
| Tunes | ? | GET | sandboxTesters |
| Tunes | ? | POST | sandboxTesters |
| Tunes | ? | DELETE | sandboxTesters/#{sandbox_tester_id} |


<details><summary>AgeRatingDeclarations ✅</summary>

| Module   | Added | Type   | Endpoint                   |
| -------- | :---: | ------ | -------------------------- |
| Tunes    | ✅    | PATCH  | ageRatingDeclarations/{id} |
</details>

<details><summary>AppCategories ❌</summary>

| Module   | Added | Type   | Endpoint                         |
| -------- | :---: | ------ | -------------------------------- |
| Tunes    | ❌    | GET    | appCategories                    |
| Tunes    | ❌    | GET    | appCategories/{id}               |
| Tunes    | ❌    | GET    | appCategories/{id}/parent        |
| Tunes    | ❌    | GET    | appCategories/{id}/subcategories |
</details>

<details><summary>AppEncryptionDeclarations ❌</summary>

| Module   | Added | Type   | Endpoint                                            |
| -------- | :---: | ------ | --------------------------------------------------- |
| Tunes    | ❌    | GET    | appEncryptionDeclarations                           |
| Tunes    | ❌    | GET    | appEncryptionDeclarations/{id}                      |
| Tunes    | ❌    | GET    | appEncryptionDeclarations/{id}/app                  |
| Tunes    | ❌    | POST   | appEncryptionDeclarations/{id}/relationships/builds |
</details>

<details><summary>AppInfoLocalizations ❌</summary>

| Module   | Added | Type   | Endpoint                  |
| -------- | :---: | ------ | ------------------------- |
| Tunes    | ✅    | POST   | appInfoLocalizations      |
| Tunes    | ❌    | GET    | appInfoLocalizations/{id} |
| Tunes    | ✅    | PATCH  | appInfoLocalizations/{id} |
| Tunes    | ❌    | DELETE | appInfoLocalizations/{id} |
</details>

<details><summary>AppInfos ❌</summary>

| Module   | Added | Type   | Endpoint                              |
| -------- | :---: | ------ | ------------------------------------- |
| Tunes    | ✅    | GET    | appInfos/{id}                         |
| Tunes    | ✅    | PATCH  | appInfos/{id}                         |
| Tunes    | ✅    | GET    | appInfos/{id}/appInfoLocalizations    |
| Tunes    | ❌    | GET    | appInfos/{id}/primaryCategory         |
| Tunes    | ❌    | GET    | appInfos/{id}/primarySubcategoryOne   |
| Tunes    | ❌    | GET    | appInfos/{id}/primarySubcategoryTwo   |
| Tunes    | ❌    | GET    | appInfos/{id}/secondaryCategory       |
| Tunes    | ❌    | GET    | appInfos/{id}/secondarySubcategoryOne |
| Tunes    | ❌    | GET    | appInfos/{id}/secondarySubcategoryTwo |
</details>

<details><summary>AppPreOrders ❌</summary>

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
| Tunes    | ❌    | DELETE | appPreviewSets/{id}                           |
| Tunes    | ❌    | GET    | appPreviewSets/{id}/relationships/appPreviews |
| Tunes    | ✅    | PATCH  | appPreviewSets/{id}/relationships/appPreviews |
| Tunes    | ❌    | GET    | appPreviewSets/{id}/appPreviews               |
</details>

<details><summary>AppPreviews ✅</summary>

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

<details><summary>AppPrices ✅</summary>

| Module   | Added | Type   | Endpoint           |
| -------- | :---: | ------ | ------------------ |
| Tunes    | ✅    | GET    | /v1/appPrices/{id} |
</details>

<details><summary>AppScreenshotSets</summary>

| Module   | Added | Type   | Endpoint                                            |
| -------- | :---: | ------ | --------------------------------------------------- |
| Tunes    | ✅    | POST   | appScreenshotSets                                   |
| Tunes    | ✅    | GET    | appScreenshotSets/{id}                              |
| Tunes    | ❌    | DELETE | appScreenshotSets/{id}                              |
| Tunes    | ❌    | GET    | appScreenshotSets/{id}/relationships/appScreenshots |
| Tunes    | ✅    | PATCH  | appScreenshotSets/{id}/relationships/appScreenshots |
| Tunes    | ❌    | GET    | appScreenshotSets/{id}/appScreenshots               |
</details>

<details><summary>AppScreenshots ✅</summary>

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
| Tunes    | ❌    | GET    | appStoreReviewAttachments/{id} |
| Tunes    | ✅    | PATCH  | appStoreReviewAttachments/{id} |
| Tunes    | ✅    | DELETE | appStoreReviewAttachments/{id} |
</details>

<details><summary>AppStoreReviewDetails</summary>

| Module   | Added | Type   | Endpoint                                             |
| -------- | :---: | ------ | ---------------------------------------------------- |
| Tunes    | ✅    | POST   | appStoreReviewDetails                                |
| Tunes    | ❌    | GET    | appStoreReviewDetails/{id}                           |
| Tunes    | ✅    | PATCH  | appStoreReviewDetails/{id}                           |
| Tunes    | ❌    | GET    | appStoreReviewDetails/{id}/appStoreReviewAttachments |
</details>

<details><summary>AppStoreVersionLocalizations</summary>

| Module   | Added | Type   | Endpoint                                            |
| -------- | :---: | ------ | --------------------------------------------------- |
| Tunes    | ✅    | POST   | appStoreVersionLocalizations                        |
| Tunes    | ❌    | GET    | appStoreVersionLocalizations/{id}                   |
| Tunes    | ✅    | PATCH  | appStoreVersionLocalizations/{id}                   |
| Tunes    | ✅    | DELETE | appStoreVersionLocalizations/{id}                   |
| Tunes    | ❌    | GET    | appStoreVersionLocalizations/{id}/appPreviewSets    |
| Tunes    | ✅    | GET    | appStoreVersionLocalizations/{id}/appScreenshotSets |
</details>

<details><summary>AppStoreVersionPhasedReleases ✅</summary>

| Module   | Added | Type   | Endpoint                           |
| -------- | :---: | ------ | ---------------------------------- |
| Tunes    | ✅    | POST   | appStoreVersionPhasedReleases      |
| Tunes    | ✅    | PATCH  | appStoreVersionPhasedReleases/{id} |
| Tunes    | ✅    | DELETE | appStoreVersionPhasedReleases/{id} |
</details>
<details>
<summary>AppStoreVersionSubmissions ✅</summary>

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
| Tunes    | ❌    | DELETE | appStoreVersions/{id}                              |
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

| Module   | Added | Type   | Endpoint                            |
| -------- | :---: | ------ | ----------------------------------- |
| Tunes    | ✅    | GET    | apps                                |
| Tunes    | ✅    | GET    | apps/{id}                           |
| Tunes    | ✅    | PATCH  | apps/{id}                           |
| Tunes    | ✅    | GET    | apps/{id}/appInfos                  |
| Tunes    | ✅    | GET    | apps/{id}/appStoreVersions          |
| Tunes    | ✅    | GET    | apps/{id}/availableTerritories      |
| Tunes    | ✅    | GET    | apps/{id}/betaAppLocalizations      |
| Tunes    | ✅    | GET    | apps/{id}/betaAppReviewDetail       |
| Tunes    | ✅    | GET    | apps/{id}/betaGroups                |
| Tunes    | ✅    | GET    | apps/{id}/betaLicenseAgreement      |
| Tunes    | ✅    | DELETE | apps/{id}/relationships/betaTesters |
| Tunes    | ✅    | GET    | apps/{id}/builds                    |
| Tunes    | ✅    | GET    | apps/{id}/endUserLicenseAgreement   |
| Tunes    | ✅    | GET    | apps/{id}/gameCenterEnabledVersions |
| Tunes    | ✅    | GET    | apps/{id}/inAppPurchases            |
| Tunes    | ✅    | GET    | apps/{id}/perfPowerMetrics          |
| Tunes    | ✅    | GET    | apps/{id}/preOrder                  |
| Tunes    | ✅    | GET    | apps/{id}/preReleaseVersions        |
| Tunes    | ✅    | GET    | apps/{id}/prices                    |
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

| Module     | Added | Type   | Endpoint                      |
| ---------- | :---: | ------ | ----------------------------- |
| TestFlight | ✅    | GET    | betaAppReviewDetails          |
| TestFlight | ✅    | GET    | betaAppReviewDetails/{id}     |
| TestFlight | ✅    | PATCH  | betaAppReviewDetails/{id}     |
| TestFlight | ✅    | GET    | betaAppReviewDetails/{id}/app |
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

| Module     | Added | Type   | Endpoint                                  |
| ---------- | :---: | ------ | ----------------------------------------- |
| TestFlight | ✅    | GET    | betaGroups                                |
| TestFlight | ✅    | POST   | betaGroups                                |
| TestFlight | ✅    | GET    | betaGroups/{id}                           |
| TestFlight | ✅    | PATCH  | betaGroups/{id}                           |
| TestFlight | ✅    | DELETE | betaGroups/{id}                           |
| TestFlight | ✅    | GET    | betaGroups/{id}/app                       |
| TestFlight | ✅    | GET    | betaGroups/{id}/relationships/betaTesters |
| TestFlight | ✅    | POST   | betaGroups/{id}/relationships/betaTesters |
| TestFlight | ✅    | DELETE | betaGroups/{id}/relationships/betaTesters |
| TestFlight | ✅    | GET    | betaGroups/{id}/betaTesters               |
| TestFlight | ✅    | GET    | betaGroups/{id}/relationships/builds      |
| TestFlight | ✅    | POST   | betaGroups/{id}/relationships/builds      |
| TestFlight | ✅    | DELETE | betaGroups/{id}/relationships/builds      |
| TestFlight | ✅    | GET    | betaGroups/{id}/builds                    |
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

| Module     | Added | Type   | Endpoint              |
| ---------- | :---: | ------ | --------------------- |
| TestFlight | ✅    | POST   | betaTesterInvitations |
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

| Module     | Added | Type   | Endpoint               |
| ---------- | :---: | ------ | ---------------------- |
| TestFlight | ✅    | POST   | buildBetaNotifications |
</details>

<details><summary>Builds</summary>

| Module   | Added | Type   | Endpoint                                           |
| -------- | :---: | ------ | -------------------------------------------------- |
| Tunes    | ✅    | GET    | builds                                             |
| Tunes    | ✅    | GET    | builds/{id}                                        |
| Tunes    | ✅    | PATCH  | builds/{id}                                        |
| Tunes    | ✅    | GET    | builds/{id}/app                                    |
| Tunes    | ✅    | GET    | builds/{id}/relationships/appEncryptionDeclaration |
| Tunes    | ✅    | PATCH  | builds/{id}/relationships/appEncryptionDeclaration |
| Tunes    | ✅    | GET    | builds/{id}/appEncryptionDeclaration               |
| Tunes    | ✅    | GET    | builds/{id}/appStoreVersion                        |
| Tunes    | ✅    | GET    | builds/{id}/betaAppReviewSubmission                |
| Tunes    | ✅    | GET    | builds/{id}/betaBuildLocalizations                 |
| Tunes    | ✅    | POST   | builds/{id}/relationships/betaGroups               |
| Tunes    | ✅    | DELETE | builds/{id}/relationships/betaGroups               |
| Tunes    | ✅    | GET    | builds/{id}/buildBetaDetail                        |
| Tunes    | ✅    | GET    | builds/{id}/diagnosticSignatures                   |
| Tunes    | ✅    | GET    | builds/{id}/icons                                  |
| Tunes    | ✅    | GET    | builds/{id}/relationships/individualTesters        |
| Tunes    | ✅    | POST   | builds/{id}/relationships/individualTesters        |
| Tunes    | ✅    | DELETE | builds/{id}/relationships/individualTesters        |
| Tunes    | ✅    | GET    | builds/{id}/individualTesters                      |
| Tunes    | ✅    | GET    | builds/{id}/perfPowerMetrics                       |
| Tunes    | ✅    | GET    | builds/{id}/preReleaseVersion                      |
</details>

<details><summary>BundleIdCapabilities ❌</summary>

| Module       | Added | Type   | Endpoint                  |
| ------------ | :---: | ------ | ------------------------- |
| Provisioning | ❌    | POST   | bundleIdCapabilities      |
| Provisioning | ❌    | PATCH  | bundleIdCapabilities/{id} |
| Provisioning | ❌    | DELETE | bundleIdCapabilities/{id} |
</details>

<details><summary>BundleIds</summary>

| Module       | Added | Type   | Endpoint                            |
| ------------ | :---: | ------ | ----------------------------------- |
| Provisioning | ✅    | GET    | bundleIds                           |
| Provisioning | ❌    | POST   | bundleIds                           |
| Provisioning | ✅    | GET    | bundleIds/{id}                      |
| Provisioning | ❌    | PATCH  | bundleIds/{id}                      |
| Provisioning | ❌    | DELETE | bundleIds/{id}                      |
| Provisioning | ✅    | GET    | bundleIds/{id}/app                  |
| Provisioning | ✅    | GET    | bundleIds/{id}/bundleIdCapabilities |
| Provisioning | ✅    | GET    | bundleIds/{id}/profiles             |
</details>

<details><summary>Certificates</summary>

| Module       | Added | Type   | Endpoint          |
| ------------ | :---: | ------ | ----------------- |
| Provisioning | ✅    | GET    | certificates      |
| Provisioning | ✅    | POST   | certificates      |
| Provisioning | ✅    | GET    | certificates/{id} |
| Provisioning | ✅    | DELETE | certificates/{id} |
</details>

<details><summary>Devices</summary>

| Module   | Added | Type   | Endpoint     |
| -------- | :---: | ------ | ------------ |
| Tunes    | ✅    | GET    | devices      |
| Tunes    | ✅    | POST   | devices      |
| Tunes    | ✅    | GET    | devices/{id} |
| Tunes    | ✅    | PATCH  | devices/{id} |
</details>

<details><summary>EndUserLicenseAgreements</summary>

| Module   | Added | Type   | Endpoint                                  |
| -------- | :---: | ------ | ----------------------------------------- |
| Tunes    | ✅    | POST   | endUserLicenseAgreements                  |
| Tunes    | ✅    | GET    | endUserLicenseAgreements/{id}             |
| Tunes    | ✅    | PATCH  | endUserLicenseAgreements/{id}             |
| Tunes    | ✅    | DELETE | endUserLicenseAgreements/{id}             |
| Tunes    | ✅    | GET    | endUserLicenseAgreements/{id}/territories |
</details>

<details><summary>FinanceReports</summary>

| Module   | Added | Type   | Endpoint       |
| -------- | :---: | ------ | -------------- |
| Tunes    | ✅    | GET    | financeReports |
</details>

<details><summary>IdfaDeclarations ✅</summary>

| Module   | Added | Type   | Endpoint              |
| -------- | :---: | ------ | --------------------- |
| Tunes    | ✅    | POST   | idfaDeclarations.     |
| Tunes    | ✅    | PATCH  | idfaDeclarations/{id} |
| Tunes    | ✅    | DELETE | idfaDeclarations/{id} |
</details>

<details><summary>InAppPurchases</summary>

| Module   | Added | Type   | Endpoint            |
| -------- | :---: | ------ | ------------------- |
| Tunes    | ✅    | GET    | inAppPurchases/{id} |
</details>

<details><summary>PreReleaseVersions</summary>

| Module   | Added | Type   | Endpoint                       |
| -------- | :---: | ------ | ------------------------------ |
| Tunes    | ✅    | GET    | preReleaseVersions             |
| Tunes    | ✅    | GET    | preReleaseVersions/{id}        |
| Tunes    | ✅    | GET    | preReleaseVersions/{id}/app    |
| Tunes    | ✅    | GET    | preReleaseVersions/{id}/builds |
</details>

<details><summary>Profiles</summary>

| Module       | Added | Type   | Endpoint                   |
| ------------ | :---: | ------ | -------------------------- |
| Provisioning | ✅    | GET    | profiles                   |
| Provisioning | ✅    | POST   | profiles                   |
| Provisioning | ✅    | GET    | profiles/{id}              |
| Provisioning | ✅    | DELETE | profiles/{id}              |
| Provisioning | ✅    | GET    | profiles/{id}/bundleId     |
| Provisioning | ✅    | GET    | profiles/{id}/certificates |
| Provisioning | ✅    | GET    | profiles/{id}/devices      |
</details>

<details><summary>RoutingAppCoverages</summary>

| Module   | Added | Type   | Endpoint                 |
| -------- | :---: | ------ | ------------------------ |
| Tunes    | ✅    | POST   | routingAppCoverages      |
| Tunes    | ✅    | GET    | routingAppCoverages/{id} |
| Tunes    | ✅    | PATCH  | routingAppCoverages/{id} |
| Tunes    | ✅    | DELETE | routingAppCoverages/{id} |
</details>

<details><summary>SalesReports</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    | salesReports |
</details>

<details><summary>Territories ✅</summary>

| Module   | Added | Type   | Endpoint |
| -------- | :---: | ------ | -------- |
| Tunes    | ✅    | GET    | territories |
</details>

<details><summary>UserInvitations</summary>

| Module   | Added | Type   | Endpoint                         |
| -------- | :---: | ------ | -------------------------------- |
| Users    | ✅    | GET    | userInvitations                  |
| Users    | ✅    | POST   | userInvitations                  |
| Users    | ✅    | GET    | userInvitations/{id}             |
| Users    | ✅    | DELETE | userInvitations/{id}             |
| Users    | ✅    | GET    | userInvitations/{id}/visibleApps |
</details>

<details><summary>Users</summary>

| Module   | Added | Type   | Endpoint                             |
| -------- | :---: | ------ | ------------------------------------ |
| Users    | ✅    | GET    | users                                |
| Users    | ✅    | GET    | users/{id}                           |
| Users    | ✅    | PATCH  | users/{id}                           |
| Users    | ✅    | DELETE | users/{id}                           |
| Users    | ✅    | GET    | users/{id}/relationships/visibleApps |
| Users    | ✅    | POST   | users/{id}/relationships/visibleApps |
| Users    | ✅    | PATCH  | users/{id}/relationships/visibleApps |
| Users    | ✅    | DELETE | users/{id}/relationships/visibleApps |
| Users    | ✅    | GET    | users/{id}/visibleApps               |
</details>

<details><summary>DiagnosticSignatures</summary>

| Module   | Added | Type   | Endpoint                       |
| -------- | :---: | ------ | ------------------------------ |
| Tunes    | ✅    | GET    | diagnosticSignatures/{id}/logs |
</details>

<details><summary>GameCenterEnabledVersions</summary>

| Module   | Added | Type   | Endpoint                                                        |
| -------- | :---: | ------ | --------------------------------------------------------------- |
| Tunes    | ✅    | GET    | gameCenterEnabledVersions/{id}/relationships/compatibleVersions |
| Tunes    | ✅    | GET    | gameCenterEnabledVersions/{id}/relationships/compatibleVersions |
| Tunes    | ✅    | GET    | gameCenterEnabledVersions/{id}/relationships/compatibleVersions |
| Tunes    | ✅    | GET    | gameCenterEnabledVersions/{id}/relationships/compatibleVersions |
| Tunes    | ✅    | GET    | gameCenterEnabledVersions/{id}/compatibleVersions               |
</details>

