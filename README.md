<!-- Document Type -->
<!DOCTYPE html>

<html>

    <head>
        <meta charset="utf-8">
        <meta name="description" content="Amazing blogsite by chathruanga">
        <meta name="keywords" conntent="web design web developmentblogging">
        <title>Test Page</title>
    </head>

    <body>
        <!-- Headings -->
        <h1>Heading One1</h1>
        <h2><marquee behavior="" derection="left">Heading One</marquee></h2>
        <h3>Heading One</h3>
        <h4>Heading One</h4>
        <h5>Heading One</h5>
        <h6>Heading One</h6>

        <!-- Navigation -->
        <a href="./blog.html">Blog Page</a>
    
         <!-- Paragraphs -->

         <p>
             <u>Sample Paragraph </u> Sample Paragraph <strong>Sample ParagraphSample Paragraph</strong> Sample Paragraph <em>ipsum dolor sit</em> amet consectetur 
             <hr>Sample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample Paragraph 
             <b>Sample Paragraph</b> Sample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample Paragraph
             <br> 
             <br>

             Sample Paragraph

             <hr>
             Sample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample ParagraphSample Paragraph
             Sample ParagraphSample ParagraphSample ParagraphSampl <a href="https://www.google.com/" target="_blank">Click Here</a>Sample ParagraphSample ParagraphSample ParagraphSamplSample ParagraphSample ParagraphSample ParagraphSamplSample ParagraphSample ParagraphSample ParagraphSampl

             <!-- List -->
             <ul type="square">
                <li>List Item 1</li>
                <li>List Item 1</li>
                <li>List Item 1
                    <ul>
                        <li>List Item 1</li>
                        <li>List Item 1</li>
                        <li>List Item 1</li>
                    </ul>
                </li>
                <li>List Item 1</li>
                <li>List Item 1</li>
                <li>List Item 1</li>
             </ul>
             <ol>
                <li>List Item 1</li>
                <li>List Item 1</li>
                <li>List Item 1</li>
                <li>List Item 1</li>
             </ol>

         </p>
         <hr>
         <!-- Table -->
         <tableborder="1">
             <thead>
                 <tr>
                     <th>Name</th>
                     <th>Email</th>
                     <th>Address</th>
                     <th>List Item</th>
                 </tr>
             </thead>
             <tbody>
                 <tr>
                     <td>Michal Franando</td>
                     <td>franando@gmail.com</td>
                     <td>No.23.5 Colombo Road, Galle</td>
                     <td>32</td>
                 </tr>
                 <tr>
                    <td>Namal</td>
                    <td>Namal@gmail.com</td>
                    <td>No.63/2, Colombo</td>
                    <td>28</td>
                </tr>
                <tr>
                    <td>Saman</td>
                    <td>Saman@gmail.com</td>
                    <td>No.63/2, Colombo</td>
                    <td>232</td>
                </tr>
             </tbody>
         </table>
         <hr>

         <!-- Froms -->
         <form action="./index.html" method="POST">
            <div>
                <label>First name</label>
                <input type="Text" Name="First Name" required>
            </div>

            <br>

            <div>
                <label>Last name</label>
                <input type="Text" Name="Last Name" required>
            </div>

            <br>

            <div>
            <label>Email</label>
            <input type="email" name="Email" placeholder="Type your Email"required>
            </div>

            <br>

            <div>
                <label>Message</label>
                <textarea name="" id="" cols="38" rows="18"></textarea required>
            </div>

            <div>
                <label>Gender</label>
                <select name="Gender" id="Gender" required> 
                    <option value="Male">Male</option>
                    <option value="Female">Female</option>
                    <option value="Other">Other</option>
                </select>
            </div>
            <br>
            <div>
                <label>Age :</label> :
                <input type="number" name="Age" required>
            </div>

            <br>

            <div>
                <label>Birthday :</label> :
                <input type="date" name="Birthday" required>
            </div>
            <br>

            <div>
                <label>Profile Picture</label>
                <input type="file" name="Upload CV" required>
            </div>

            <br>

            <div>
                <label>Favourite Food :</label> :
                <input type="checkbox" name="Apple" value="Apple"><label> Apple</label>
                <input type="checkbox" name="Mango" value="Mango"><label> Mango</label>
                <input type="checkbox" name="Cake" value="Cake"><label> Cake</label>
            </div>
            <br>
            <div>
                <label>User Type :</label> :
                <input type="radio" id="static" name="Usertype" value="static"><label> Static</label>
                <input type="radio" id="dynamic" name="Usertype" value="dynamic"><label> Dynamic</label>
             </div>
             <br>
             <div>
                 <input type="Submit" value="Submit" name="submit">
             </div>
             <br>

             <hr>
             <br>

             <!-- Button -->
             <button>Click Me</button>
             <br>
             <br><hr>

             <!-- Image -->
             <a href="./books.jpg" target="_blank">
            <img src="./books.jpg" alt="This is an Image" height="300 " width="500">
        </a>

        <!-- Quotations -->
        <blockquote cite="www.google.com">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur, soluta temporibus quia nemo voluptatem architecto! Repellendus est esse consequatur labore, aliquam iusto adipisci animi neque incidunt quidem, dolores assumenda! Nobis.
        </blockquote>
        <hr>

        <!-- Abbreviation -->
        <p>
            The <abbr title="World Wide Web"> WWW</abbr> is amazing thing that descoverd ever.
        </p>
        <section>
            <p>HTML Crash Cource By <cite>TripleBee</cite></p>
        </section>

        <hr>
            
        <footer>
            <p>Copyright &copy; 2021</p>
        </footer>

         </form>

    </body>

</html>
