# oop-coding-convention

Tất cả phải được viết bằng tiếng Anh

1. Class:
  - Tên của class nên được đặt bằng chữ cái viết hoa theo quy tắc ***`CamelCase`***.
  - Tên class nên là danh từ hoặc cụm từ miêu tả đúng chức năng và mục đích của class.

<br/>
    
2. Method:
  - Tên của method nên được đặt bằng chữ cái viết thường theo quy tắc ***`camelCase`***.
  - Tên method nên miêu tả hành động mà method thực hiện.
 
<br/>
      
3. Property:
  - Tên của property nên được đặt bằng chữ cái viết thường theo quy tắc ***`camelCase`***.
  - Tên property nên miêu tả thuộc tính của đối tượng.

<br/>


Ví dụ
```php
class ShoppingCart {
    private $itemCount;

    public function getItemCount() {
        return $this->itemCount;
    }

    public function setItemCount($count) {
        $this->itemCount = $count;
    }

    public function addItem($item) {
        // Thêm một mục vào giỏ hàng
    }
}
```
