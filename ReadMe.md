Using the provided data (tickets.json and users.json) write a simple command line application
to search the data and return the results in a human readable format.
* Feel free to use libraries or roll your own code as you see fit. However, please do not use a
database or full text search product as we are interested to see how you write the solution.
* Where the data exists, values from any related entities should be included in the results, i.e.
searching tickets should return their assigned user and searching users should return their
assigned tickets.
* The user should be able to search on any field. Full value matching is fine (e.g. "mar" won't
return "mary").
* The user should also be able to search for missing values, e.g. where a ticket does not have
an assignee_id.
Search can get pretty complicated pretty easily, we just want to see that you can code a basic
but efficient search application. Ideally, search response times should not increase linearly as
the number of documents grows. You can assume all data can fit into memory on a single
machine.
