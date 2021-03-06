### 创建页面菜单

[POST] /v1/menu/m/:menu_id

| 参数      | 类型       | 说明                                        | 必选 |
| --------- | ---------- | ------------------------------------------- | ---- |
| name      | `string`   | 菜单名                                      | \*   |
| url       | `string`   | 菜单对应的页面 url                          |      |
| icon      | `string`   | 菜单图标                                    |      |
| accession | `[]string` | 菜单对应的权限                              |      |
| sort      | `int`      | 菜单排序, 值越大，菜单越靠前                |      |
| parent_id | `string`   | 该菜单的父级菜单, 如果 不填写，则为顶级菜单 |      |

### 获取页面菜单列表

[GET] /v1/menu

### 获取菜单详情

[GET] /v1/menu/m/:menu_id

### 更新页面菜单

[PUT] /v1/menu/m/:menu_id

| 参数      | 类型       | 说明                         | 必选 |
| --------- | ---------- | ---------------------------- | ---- |
| name      | `string`   | 菜单名                       |      |
| url       | `string`   | 菜单对应的页面 url           |      |
| icon      | `string`   | 菜单图标                     |      |
| accession | `[]string` | 菜单对应的权限               |      |
| sort      | `int`      | 菜单排序, 值越大，菜单越靠前 |      |
| parent_id | `string`   | 该菜单的父级菜单             |      |

### 删除页面菜单

[DELETE] /v1/menu/m/:menu_id

