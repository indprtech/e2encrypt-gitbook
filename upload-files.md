# 🗃 Upload Files

**Loading File Library**

```php
public $file;
function __construct(){
    $this->file = $this->library("file");
}
```

| Method              | Arguments         | What does this do?         | Req\*? |
| ------------------- | ----------------- | -------------------------- | :----: |
| setFileName         | $fileName         | Sets the File Name         |   Yes  |
| setUploadPath       | $path             | Sets the Upload Path       |   Yes  |
| setAllowedFileTypes | $array            | Sets the alowed file types |   No   |
| setMaxSize          | int Bytes         | Sets Max File Size         |   Yes  |
| setField            | string Form Field | Sets Field from POST Value |   Yes  |

### Upload Files

```php
$file->setFileName("_FILE.jpg");
$file->setUploadPath("upload");
$file->setAllowedFileTypes(["jpg","png","jpeg"]);
$file->setMaxSize(50000);
$file->setField("file");

$file->upload(); //=> ["FILE_NAME" => ""]
```
