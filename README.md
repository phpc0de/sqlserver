# GORM SQL Server Driver

## USAGE

```go
import (
  "gorm.io/driver/sqlserver"
  "github.com/phpc0de/backupgorm"
)

// github.com/denisenkom/go-mssqldb
dsn := "sqlserver://gorm:LoremIpsum86@localhost:9930?database=gorm"
db, err := gorm.Open(sqlserver.Open(dsn), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
