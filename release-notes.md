# Release 1.0.11

## What's Changed
* Jobs should be fetched and scheduled based upon the selected Shop(#2r65b1c) by @disha1202 in https://github.com/hotwax/job-manager/pull/228
* Added shopify config info at menu footer(#2q9mut9) by @disha1202 in https://github.com/hotwax/job-manager/pull/220
* Implemented: Miscellaneous page in job-manager(#364ttxy) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/214


**Full Changelog**: https://github.com/hotwax/job-manager/compare/v1.0.10...v1.0.11


# Release 1.0.10

## What's Changed
* Implemented functionality to save auto cancel days(#2cxr1cx) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/213 & @disha1202 in https://github.com/hotwax/job-manager/pull/218
* Fixed: the issue of service time being passed when using run now functionality for pending jobs(#2r0jq44) by @ymaheshwari1 in https://github.com/hotwax/job-manager/pull/222
* Fixed: missing productStoreId and shopifyConfigId for Job while using runNow (#2r0jq44) by @adityasharma7 in https://github.com/hotwax/job-manager/pull/223
* Update contribution guideline in Readme file(#2r0kmb3) by @azkyakhan in https://github.com/hotwax/job-manager/pull/224
* Fixed: code to get 'eComStores' in 'getProfile' action instead of calling 'getEcomStores' action (#257v6ck). by @meet-aniket in https://github.com/hotwax/job-manager/pull/165, @rathoreprashant in https://github.com/hotwax/job-manager/pull/200 & @disha1202 in https://github.com/hotwax/job-manager/pull/226
* Implemented: Code to check if user has permission to access the app(#2hr41aq) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/221
* Improved: runTime set to start of the next day for 'EVERYDAY' frequency (#2ftb2vw)  by @rathoreprashant in https://github.com/hotwax/job-manager/pull/206 & @disha1202 in https://github.com/hotwax/job-manager/pull/225
* Implemented: Add additional job actions to job config component(#364tt29) by @disha1202 in https://github.com/hotwax/job-manager/pull/216
* Implemented: additional job actions, to job config component (#364tt29) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/212
* Fixed: Run now functionality for the job manager is not working correctly (#2rhqqf7) by @adityasharma7 in https://github.com/hotwax/job-manager/pull/229
* Implemented: functionality to have option to run jobs within 1 min(#2rhruw9) by @ymaheshwari1 in https://github.com/hotwax/job-manager/pull/230
* Fixed: Not able to open job update section on Pipeline page for some jobs (#2rht6hk) by @adityasharma7 in https://github.com/hotwax/job-manager/pull/231


**Full Changelog**: https://github.com/hotwax/job-manager/compare/v1.0.9...v1.0.10


# Release 1.0.9

## What's Changed
* Fixed: DateTime component has different hour cycle on different devices(#2dmq8ja) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/180
* Implemented: Feature to run scheduled job right away(#364ttgf) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/211
* Implemented support to store user preference for selected product store (#2f2h8hu) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/219
* Implemented support to store user preference for selected product store (#2f2h8hu) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/197
* Implemented: Add option to select shopify config from settings page(#2q9mut9) by @disha1202 in https://github.com/hotwax/job-manager/pull/217


**Full Changelog**: https://github.com/hotwax/job-manager/compare/v1.0.8...v1.0.9

# Release 1.0.8

## What's Changed
* Fixed: issue of auto cancel job check is not reflected on UI when the job is scheduled(#28u4g5n) by @ymaheshwari1 in https://github.com/hotwax/job-manager/pull/189
* Implemented: Added feature to schedule job that updates ship from dates for pre-order and backorder items on Shopify(#2ftbca6) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/190
* Implemented: functionality to schedule process upload job from initial load page(#2ftaz3n) by @ymaheshwari1 in https://github.com/hotwax/job-manager/pull/192
* Implemented: code to add functionality to subscribe or unsubscribe a webhook(#2ftb11u) by @ymaheshwari1 in https://github.com/hotwax/job-manager/pull/191
* Implemented | Web hooks card on Product View Page by @rvutd in https://github.com/hotwax/job-manager/pull/178
* Fixed: the issue of null value being passed in payload when scheduling a job(#2hjh89u) by @ymaheshwari1 in https://github.com/hotwax/job-manager/pull/195
* Fixed: Instance URL should be case insensitive(#2ft61zw) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/196
* Improved: runTime set to start of the day for 'EVERYDAY' frequency else current time (#2ftb2vw) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/193
* Fixed: lastShopifyOrderId should be required for bulk order import on initial load page (#2krc8dw) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/198
* Updated: code to fetch shopifyConfigId corresponding to product store(#2kbnqzb) by @disha1202 in https://github.com/hotwax/job-manager/pull/199
* Revert "Improved: runTime set to start of the day for 'EVERYDAY' frequency else current time (#2ftb2vw)" by @adityasharma7 in https://github.com/hotwax/job-manager/pull/201
* Fixed: After refreshing and then clicking the back button the user is  redirected to the pipeline page(job-manager(#2deygnv) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/176
* Fixed: Orders are not imported with multiple shopify configuration(#2mky5yp) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/204
* Fixed: Orders are not imported with multiple shopify configuration(#2mky5yp) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/205
* Improved label to "eCom Store" on Settings page (#23tw4yf)  by @rathoreprashant in https://github.com/hotwax/job-manager/pull/203
* Fixed: code to close sliding option for skip action when it completes (#2ebeqzf). by @meet-aniket in https://github.com/hotwax/job-manager/pull/182
* Implemented: code to display a toast when the job is not present (#2fyy5bd) by @rathoreprashant in https://github.com/hotwax/job-manager/pull/202
* Fixed: Removed code which passes entityName for the calls done in findJobs API(#2np1py0) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/208
* Implemented: Added enum description to job config component(#364trwn) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/207
* Fixed: Code to use a single service to subscribe webhook(#2fz59a8) by @shashwatbangar in https://github.com/hotwax/job-manager/pull/194
* Fixed: Issue passing list to performFind with GET method (#2a2ancm) by @adityasharma7 in https://github.com/hotwax/job-manager/pull/185

## New Contributors
* @rvutd made their first contribution in https://github.com/hotwax/job-manager/pull/178

**Full Changelog**: https://github.com/hotwax/job-manager/compare/v1.0.7...v1.0.8
