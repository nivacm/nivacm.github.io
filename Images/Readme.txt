<header>
            <h1>Get in touch!</h1>
        </header>

        <form action="https://formspree.io/your-formspree-code" method="post">
            <div class= "form-item">
                <label for= "name">Name</label>
                <input type="text" id= "name" name="name"> 

            </div>
            <div class="form-item">
                <label for="mail">Email</label>
                <input type="email" id="mail" name="email">
            </div>
            <div class="form-item">
                <label for="message">Message</label> 
                <textarea id="message" name="message"></textarea>
            </div>
            <div class="form-item">
                <button type="submit">Send!</button>
             </div>
        </form>


body {
    background-color: #475F94;
    color: #fff;
    font-family: "Gill Sans", sans-serif;
}

header {
    border-bottom: 2px solid #FDDC5C;
    text-align: center;
}

form {
    margin: 50px auto;
    width: 90%;
}

.form-item {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 5px;
}

.form-item label {
    flex-basis: 150px;
    font-size: 22px;
}

.form-item input,
.form-item textarea {
    flex-basis: 50%;
    border: 2px solid #FDDC5C;
}

.form-item input:hover,
.form-item textarea:hover {
    border: 2px solid #FA4224;
}

.form-item input,
.form-item textarea,
.form-item button {
    border: 2px solid #FDDC5C;
    background-color: #FFF;
    padding: 5px;
    font-size: 18px;
}

.form-item button:hover {
    border: 2px solid #FA4224;
    background-color: #FA4224;
    color: #FFF;
}

.form-item button {
    width: 100px;
}
