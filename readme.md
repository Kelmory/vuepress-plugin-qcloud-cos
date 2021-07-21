# Vuepress-plugin-qcloud-cos (Pending)
Host your vuepress images onto Tencent Cloud COS system. This plugin aims to offload images from the original hosting site that is with limited export bandwidth.

## Workflow
Pending.

## TODO List
- [x] Basic Plugin Template: create a plugin template to start.
- [x] Integrate Tencent COS SDK (JS version).
- [ ] Develop the management process:
  - [ ] Design the comprehensive configure file: use `config.js` for specifying upload range and a separate file (*gitignored*) to setup account privileges;
  - [ ] COS connection service: account setup and connection provider.
  - [ ] Collection service: collect and process images before uploading.
  - [ ] Upload service: for uploading the images given.
  - [ ] Replacement service: replace the links to images inside the markdown files.