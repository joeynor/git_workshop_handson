# git_workshop_handson

```
import 'package:flutter/material.dart';

import 'package:get/get.dart';
import 'package:uniflow_mobile/shared/app_data.dart';

import 'app/routes/app_pages.dart';

void main() async {
  await AppData().init();
  runApp(
    GetMaterialApp(
      title: "Uniflow",
      initialRoute: AppPages.INITIAL,
      getPages: AppPages.routes,
    ),
  );
}
```

## 2nd header

| Syntax | Desc |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


### 3rd header

I need to highlight these ==very important words==.
I need to highlight these __very important words__.
