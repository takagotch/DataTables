### DataTables
---
https://www.datatables.net/

```js
$(document).ready(function(){
  $('#example').DataTable();
});

$(document).ready(function(){
  $('#example').DataTable({
    "paging": false,
    "ordering": false,
    "info": false
  });
});

$(document).ready(funciton(){
  $('#example').DataTable({
    "order": [[ 3, "desc" ]]
  });
});

$(document).ready(function(){
  $('#example').DataTable({
    columnDefs: [{
      targets: [ 0 ],
      orderData: [ 0, 1 ]
    }, {
      targets: [ 1 ],
      orderData: [ 1, 0 ]
    }, {
      targets: [ 4 ],
      orderData: [ 4, 0 ]
    }]
  });
});

```

```
```

```
```

