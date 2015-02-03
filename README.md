# LESS-Framework
My custom LESS framework

# Setup

Start by removing the import for the variation you are not using(desktop or mobile). Remove the folder as well if you don't want to risk being confused at all.
When setting the media queries in variables.less remove the media queries you will not be using.

form examples

<form class="form-horizontal">
  <div class="form-group">
    <label for="inputEmail3" class="sm-2 control-label">Email</label>
    <div class="sm-10">
      <input type="email" class="form-control" placeholder="Email">
    </div>
  </div>
  <div class="form-group">
    <label for="inputPassword3" class="sm-2 control-label">Password</label>
    <div class="sm-10">
      <input type="password" class="form-control" placeholder="Password">
    </div>
  </div>
  <div class="form-group">
    <div class="sm-offset-2 sm-10">
      <div class="checkbox">
        <label>
          <input type="checkbox"> Remember me
        </label>
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="sm-offset-2 sm-10">
      <button type="submit" class="btn">Sign in</button>
    </div>
  </div>
</form>


<select class="form-control">
  <option>1</option>
  <option>2</option>
  <option>3</option>
  <option>4</option>
  <option>5</option>
</select>