# context_patch
if you are using mke2fs+e2fsdroid or mkfs.erofs repack android image ,you can use it to patch file_context

# Usage
if there have a vendor file
vendor:
 - vendor (dir):(many files)
 - config (dir):
   - vendor_fs_config    
   - vendor_file_context    
```shell
python context_patch.py ./vendor/vendor ./vendor/config/vendor_file_context
```
