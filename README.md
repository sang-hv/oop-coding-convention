# oop-coding-convention

Tất cả phải được viết bằng tiếng Anh

1. Class, Abstract:
  - Tên của class, abstract nên được đặt bằng chữ cái viết hoa theo quy tắc ***`CamelCase`***.
  - Tên class nên là danh từ hoặc cụm từ miêu tả đúng chức năng và mục đích của class.
  - Đối với các class abstract, thường có thêm tiền tố "Abstract" hoặc "Base". Ví dụ: PersonAbstract, AnimalAbstract.
  - Đối với các Trait, thường có thêm tiền tố "Trait". Ví dụ: MyTrait.

<br/>
    
2. Method:
  - Tên của method nên được đặt bằng chữ cái viết thường theo quy tắc ***`camelCase`***.
  - Tên method nên miêu tả hành động mà method thực hiện.
 
<br/>
      
3. Property:
  - Tên của property nên được đặt bằng chữ cái viết thường theo quy tắc ***`camelCase`***.
  - Tên property nên miêu tả thuộc tính của đối tượng.

<br/>

4. Interface:
  - Với interface, thường nên sử dụng các tính từ hoặc các trạng từ để đặt tên, bởi vì interface thường đại diện cho một tập hợp các phương thức hoặc thuộc tính chung, mà các class có thể triển khai. Ví dụ: Serializable, Comparable, Runnable,...



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
