# shinyalert 1.1

2020-04-29

- New feature (#11): `inputId` parameter added, which allows you to set the input ID that is used to retrieve the return value of the modal
- New feature (#12): support chaining modals, you can now call a shinyalert modal in the callback of another modal
- Fixed bug (#19) - alerts with an R callback were very slow when the environment had a large object
- New feature (#23): Support using `shinyalert` within Rmarkdown documents
- The return value can now be triggered even if the same input value is used consecutively (only if using shiny version 1.1)
- Documentation changes
- Improvements to demo shiny app UI

# shinyalert 1.0

2018-02-12

Initial release
