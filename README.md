# Mini CRM SQL Project

A simple SQL-based CRM database project for managing customers, orders, and shipping records. This project demonstrates basic SQL queries, table relationships, and customer data filtering.
---

## Features
- Customer database management
- Order tracking
- Shipping status monitoring
- SQL filtering using `WHERE`
- Relational table structure
---

## Database Tables

### Customers
| Column | Type |
|---|---|
| customer_id | int |
| first_name | varchar |
| last_name | varchar |
| age | int |
| country | varchar |

### Orders
| Column | Type |
|---|---|
| order_id | integer |
| item | varchar |
| amount | integer |
| customer_id | integer |

### Shippings
| Column | Type |
|---|---|
| shipping_id | integer |
| status | varchar |
| customer | integer |
---

## Example Queries

```sql
SELECT * FROM Customers
WHERE age > 25;
```

```sql
SELECT * FROM Shippings
WHERE status = 'Delivered';
```

---

## Skills Used
- SQL
- Database Management
- Data Filtering
- Relational Database Basics

---

## Screenshot
https://drive.google.com/file/d/12LZlA03v62ea67FV0wep6U7bgoykyzqn/view?usp=drivesdk

---

## Future Improvements
- Add JOIN queries
- Create sales pipeline system
- Build frontend dashboard
- Connect with CRM web application
