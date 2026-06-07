---

---

--- Before Day-4 ---
I already knew that websites and applications communicate over the internet using HTTP requests. However, I was not familiar with inspecting network traffic using Chrome DevTools, understanding API requests in detail, or creating and testing my own FastAPI endpoints.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Day-4 Checklist

* [x] I know the 5 core HTTP methods (GET, POST, PUT, PATCH, DELETE) and what each is used for
* [x] I can read a status code and know what went wrong — e.g., 401 vs. 403 vs. 404 vs. 500
* [x] I can open Chrome DevTools Network tab, find a request, and inspect its headers, payload, and response
* [x] I can copy a browser request as a `curl` command and run it in the terminal
* [x] I can change the `User-Agent` in the browser and see the change in the Network tab
* [x] I can use `curl` to make a GET request with query parameters and a POST request with a JSON body
* [x] I have a running FastAPI app with at least two endpoints (`GET /health` and `POST /echo`)
* [x] I can test my API using the Swagger UI at `/docs` and via `curl` from the terminal

--- After Day-4 ---
I learned how browsers communicate with servers through HTTP requests and responses, how to inspect live network traffic using Chrome DevTools, and how to replicate browser requests using curl. I also learned the practical differences between HTTP methods, how status codes help diagnose problems, and how FastAPI can be used to quickly create and test APIs through Swagger and the command line.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

--- Feedback (Suggestions for the TDS Team) ---
The Chrome DevTools demonstrations were particularly useful because they connected theoretical HTTP concepts with real-world browser behavior. The FastAPI examples also helped clarify how APIs are created and tested. Additional guided exercises involving request inspection and API debugging would further improve understanding.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

---

---

Personal Notes:

* DevTools Network tab is useful for inspecting requests and responses.
* Status code 200 indicates success.
* Status code 401 means unauthorized.
* Status code 403 means forbidden.
* Status code 404 means resource not found.
* Status code 500 indicates a server-side error.
* FastAPI automatically generates Swagger documentation at `/docs`.
* `curl` can be used to reproduce browser requests from the terminal.
