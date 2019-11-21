# form-with-inline-inputs
In order to conserve design space, you may need to have your form inputs inline rather than stacked. Bootstrap makes this incredibly easy to do.

## Tutorial
For detailed instruction's, view Solodev's [How to Use bootstrap to Create a Form with Inline Inputs](https://www.solodev.com/blog/web-design/bootstrap/how-to-use-bootstrap-to-create-a-form-with-inline-inputs-.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/xg63dph4/).

## HTML
The tutorial contains the following basic HTML markup.

```
   <div class="container p-5" id="bottom-form-area">
      <form name="contentForm" method="post" action="#" role="form">
        <div id="bottom-signup-form">
          <div class="row mt-1 d-md-flex align-items-end">
            <div class="form-group col-lg-3 px-md-2 pt-md-2 mt-lg-0 pb-2 position-relative">
              <label for="name">Name <span>*</span></label>
              <input type="text" class="form-control border-top-1 border-left-1 border-right-1" placeholder="John Doe">
            </div><!-- form-group -->
            <div class="form-group col-lg-3 px-md-2 pt-md-2 mt-lg-0 pb-2 position-relative">
              <label for="email">Email <span>*</span></label>
              <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" class="form-control border-top-1 border-left-1 border-right-1" placeholder="you@example.com">
              <div class="position-absolute bottom-0 left-0 pl-2"></div>
            </div><!-- form-group -->
            <div class="form-group col-lg-3 px-md-2 pt-md-2 mt-lg-0 pb-2 position-relative">
              <label for="phone">Phone <span>*</span></label>
              <input type="phone" placeholder="123-456-7890" name="phone" class="form-control border-top-1 border-left-1 border-right-1">
              <div class="position-absolute bottom-0 left-0 pl-2"></div>
            </div><!-- form-group -->
            <div class="form-group col-lg-3 mt-lg-0 pb-2 text-center text-lg-left mt-4">
              <input type="submit" value="Submit" class="btn btn-primary text-white w-250p">
            </div>
          </div>
        </div>
      </form>
     </div>
```

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```

