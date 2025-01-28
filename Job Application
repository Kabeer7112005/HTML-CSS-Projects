# Job-application
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Job Application</title>
</head>
  <!-- 
  This below code belongs to CSS
  -->
<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body{
    background-color: rgb(230, 242, 253);
  }
  .container{
    margin: 0 auto;
   max-width: 900px;
  }
  .contentbox{
    max-width: 600px;
    padding: 20px;
    background-color: white;
    margin: 0 auto;
    margin-top: 50px;
    box-shadow:4px 3px 5px black ;
    border-radius: 10px;
  }
  .small{
    font-size: 20px;
    padding-left: 10px;
  }
  .formcontainer{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(200px,1fr));
    gap: 20px;
    margin-top: 20px;
  }
  .form_control{
    display: flex;
    flex-direction: column;
  }
  label{
    font-size: 15px;
    margin-bottom: 5px;
  }
  input,select,textarea{
    padding: 6px 10px;
    border: 1px solid black;
    border-radius: 4px;
    font-size: 15px;
  }
  input,textarea:focus{
    outline-color: rgb(241, 59, 59);
  }
  .button{
    display: flex;
    justify-content: flex-end;
  }
  button{
   background-color: rgb(245, 78, 78);
   border-radius: 8px;
   border: 2px solid transparent;
   padding: 5px 10px;
   color: white;
   margin-top: 15px;
  }
  button:hover{
    background-color: rgb(240, 28, 28);
    color: black;
  }
  .textarea_control{
    grid-column: 1/span 2;
  }
  .textarea_control textarea{
    width: 100%;
  }

  @media (max-width:460px){
    textarea_control{
      grid-column: 1 / span 1;
    }
  }

</style>
<!--CSS code ends here-->
<body>
  <div class="container">
    <div class="contentbox">
      <h1>Job Application<span class="small">(Web)</span></h1>
      <form>
        <div class="formcontainer">
          <div class="form_control">
            <label for="firstname">First Name</label>
            <input type="text" id="firstname" required>
          </div>
          <div class="form_control">
            <label for="lastname">Last Name</label>
            <input type="text" id="lastname" required>
          </div>
          <div class="form_control">
            <label for="email">Email</label>
            <input type="email" id="email"placeholder="xyz@gmail.com" required>
          </div>
          <div class="form_control">
            <label for="jobrole">Job Role</label>
            <select id="jobrole">
              <option value="">Select Option</option>
              <option value="fullstack">Full Stack</option>
              <option value="frontend">Front-End</option>
              <option value="backend">Back-End</option>
              <option value="ui/ux">UI/UX Dev</option>
            </select>
          </div>
          <div class="textarea_control">
            <label for="address">Enter Adress</label>
            <textarea  id="address" rows="5" cols="50"  ></textarea>
          </div>
          <div class="form_control">
            <label for="city">City</label>
            <input type="text" id="city" required>
          </div>
          <div class="form_control">
            <label for="pincode">Pincode</label>
            <input type="tel" id="pincode" required>
          </div>
          <div class="form_control">
            <label for="date">Date</label>
            <input type="date" value="2000-01-01" id="date" required>
          </div>
          <div class="form_control">
            <label for="file">Upload Your CV</label>
            <input type="file"  id="username" required>
          </div>
        </div>
        <div class="button">
          <button type="submit">Apply Now</button>
        </div>
      </form>

    </div>
  </div>
</body>
</html>
