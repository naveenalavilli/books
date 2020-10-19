# Get A Book
Repository of free e-books.

Hosted on [www.getabook.ml](https://www.getabook.ml)

Note: This is a public repository, and the books are contributed by anyone on GitHub.
No responsibility is assumed over copyright or any other issues.

# Contribute
* Fork this project
* Update Index.html
* Create a pull request.


This website uses Bootstrap 4.0 , for aesthetics. Please use the List component like below to add your book.

* For new category of books

      ```
       <div class="card mb-5">
          <div class="card-header">
            <h4>BOOK CATEGORY</h4>
          </div>
          <ul class="list-group list-group-flush">            
           <li class="list-group-item">
              <a href=" LINK TO BOOK " target="_blank">
                <Book Name>
              </a>
              <span class="text-muted text-right"> - AUTHOR NAME</span>
            </li>
          </ul>
        </div>
        ```
        
* For existing Category , just add a List Item      

          ```
          <li class="list-group-item">
              <a href=" LINK TO BOOK " target="_blank">
                <Book Name>
              </a>
              <span class="text-muted text-right"> - AUTHOR NAME</span>
            </li>
            ```
