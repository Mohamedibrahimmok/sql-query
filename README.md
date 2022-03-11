# sql-query
SELECT  BillingCountry as Countries ,count(InvoiceId) as Invoices
FROM Invoice
GROUP by Countries
ORDER by Invoices DESC 
LIMIT 5

