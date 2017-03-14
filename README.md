Using:

1. Copy to your src folder.
2. In your js add following code
  `Vue.use(ClientTable, [], false, require('./template.js')('client'));`
3. To enable grouping set following optons:
  
  `options:{  
  .......
  group:true,
  orderBy:{column:'<columntogroup>', ascending: true },
  .........
  }`
