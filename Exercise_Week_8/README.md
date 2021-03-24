# Python Exercise 08

## Exercise 1

1. Go to this website: [https://www.komplett.dk/category/21064/mobil/mobiltelefoner](https://www.komplett.dk/category/21064/mobil/mobiltelefoner)
2. Use BeautifulSoup, to select the name and price for the cellphones (hint: look for class="product-price" to begin with).
3. Create a mysql table called cellphones, with columns id, name, price.
4. Insert the cellphone data into the cellphones table, using a mysql connector and cursor.

## Exercise 2
1. Create a restful webservice that can respond to the following requests, by collecting/adding data from the cellphones table:

| Method | URL                 | Response                                                     | Description                                         |
| ------ | ------------------- | ------------------------------------------------------------ | --------------------------------------------------- |
| GET    | /api/cellphones/all | [{"id":1, "name":"Samsung Galaxy S20", "price":5999},{},{}...] | Returns all the cellphone objects from the database |
| POST   | /api/cellphones     | POST json: {"name":"One Plus", "price":12345}                | Adds a new cellphone object to the database         |

## Exercise 3
1. Select the data from the endpoints, using a request object.
2. Make a sorted bar chart of the cellphones, where x-axis is names, and y-axis is price.

#### Made by NewBiz:

- Nicklas Nielsen (cph-nn161@cphbusiness.dk)
- Mathias Haugaard (cph-mn556@cphbusiness.dk)
- Nikolaj Larsen (cph-nl174@cphbusiness.dk)