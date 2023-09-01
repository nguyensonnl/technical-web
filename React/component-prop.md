### React Component

Components giúp phân chia các UI (giao diện người dùng) thành các phân nhỏ để dễ dàng quản lý và tái sử dụng

Giả sử mình có một website gồm nhiều phần bố cục khác nhau và mình muốn chia nhỏ các phần ra để dễ quản lý

### Cách khai báo 1 component
Cách 1: Sử dụng class (Không khuyến khích)

```javascript
import { Component } from 'react'

class ComponentA extends Component {

    render(){
        return <div>Nội dung component</div>
    }
}

export default ComponentA
```

Cách 2: Sử dụng hook

```javascript
export default function ComponentA(){
    return <div>Nội dung Component</div>
}
```

Hoặc arrow function
```javascript
const ComponentA = () => {
    return <div>Nội dung Component</div>
}

export default ComponentA
```

Tùy thuộc vào bạn chọn hook hay class mà chọn cho mình cách khai báo phù hợp,  nên sử dụng cách arrow function vì nó ngắn gọn