# sina
Get real-time quotes form  http://hq.sinajs.cn



## attention

Use tushare stock code format.
eg: 000001.SZ , NOT sz000001 !!!

## usage
```
import "github.com/charlesren/sina"

data := sina.GetData("000027.SZ")
fmt.Println("Highest value of today is:", data.High)
```