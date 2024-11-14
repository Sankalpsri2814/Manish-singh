#include <bits/stdc++.h>
using namespace std;
void geeks()
{
    int var = 20;

    // declare pointer variable
    int* ptr;

    // note that data type of ptr and var must be same
    ptr = &var;

    // assign the address of a variable to a pointer
    cout << "Value at ptr = " << ptr << "\n";
    cout << "Value at var = " << var << "\n";
    cout << "Value at *ptr = " << *ptr << "\n";
}
// Driver program
int main() 
{ 
#include <bits/stdc++.h>
using namespace std;

// Function to recursively remove adjacent duplicates
string rremove(string s) {
    // Create an empty string to build the result
    string sb = ""; 

    // Get the size of the input string
    int n = s.size(); 

    // Iterate over the length of current string
    for (int i = 0; i < n; i++) {
        bool repeated = false;

        // Check if the current characteris the same
        // as the next one
        while (i + 1 < n && s[i] == s[i + 1]) {
            repeated = true;  // Mark as repeated
          
            // Skip the next character
            // since it's a duplicate
            i++;  
        }

        // If the character was not repeated,
        // add it to the result string
        if (!repeated) sb += s[i];
    }

    // If no changes made, return the result string
    if (n == sb.length())
        return sb;
    // Otherwise, recursively call the function 
    // to check for more duplicates
    return rremove(sb);
}

int main() {
    string s = "geeksforgeek";  
    string result = rremove(s);  
    cout << result << endl;
    
    return 0;
}
 A patent license is "discriminatory" if it does not include within
the scope of its coverage, prohibits the exercise of, or is
conditioned on the non-exercise of one or more of the rights that are
specifically granted under this License.  You may not convey a covered
work if you are a party to an arrangement with a third party that is
in the business of distributing software, under which you make payment
to the third party based on the extent of your activity of conveying
the work, and under which the third party grants, to any of the
parties who would receive the covered work from you, a discriminatory
patent license (a) in connection with copies of the covered work
conveyed by you (or copies made from those copies), or (b) primarily
for and in connection with specific products or compilations that
contain the covered work, unless you entered into that arrangement,
or that patent license was granted, prior to 28 March 2007.
Bots: Chatbots assist clients to get to the point quickly by answering inquiries and referring them to relevant resources and products at any time of day or night. To be effective, chatbots must be fast, smart, and easy to use, To accomplish this, chatbots employ NLP to understand language, usually over text or voice-recognition interactions
Supporting Invisible UI: Almost every connection we have with machines involves human communication, both spoken and written. Amazon’s Echo is only one illustration of the trend toward putting humans in closer contact with technology in the future. The concept of an invisible or zero user interface will rely on direct communication between the user and the machine, whether by voice, text, or a combination of the two. NLP helps to make this concept a real-world thing.
Smarter Search: NLP’s future also includes improved search, something we’ve been discussing at Expert System for a long time. Smarter search allows a chatbot to understand a customer’s request can enable “search like you talk” functionality (much like you could query Siri) rather than focusing on keywords or topics. Google recently announced that NLP capabilities have been added to Google Drive, allowing users to search for documents and content using natural language.
Future Enhancements: 
Companies like Google are experimenting with Deep Neural Networks (DNNs) to push the limits of NLP and make it possible for human-to-machine interactions to feel just like human-to-human interactions.
Basic words can be further subdivided into proper semantics and used in NLP algorithms.
The NLP algorithms can be used in various languages that are currently unavailable such as regional languages or languages spoken in rural areas etc.
Translation of a sentence in one language to the same sentence in another Language at a broader scope.
Conclusion
In conclusion, the field of Natural Language Processing (NLP) has significantly transformed the way humans interact with machines, enabling more intuitive and efficient communication. NLP encompasses a wide range of techniques and methodologies to understand, interpret, and generate human language. From basic tasks like tokenization and part-of-speech tagging to advanced applications like sentiment analysis and machine translation, the impact of NLP is evident across various domains. As the technology continues to evolve, driven by advancements in machine learning and artificial intelligence, the potential for NLP to enhance human-computer interaction and solve complex language-related challenges remains immense. Understanding the core concepts and applications of Natural Language Processing is crucial for anyone looking to leverage its capabilities in the modern digital landscape.
Natural Language Processing – FAQs
What are NLP models?
NLP models are computational systems that can process natural language data, such as text or speech, and perform various tasks, such as translation, summarization, sentiment analysis, etc. NLP models are usually based on machine learning or deep learning techniques that learn from large amounts of language data.
# Python code to demonstrate variance() 
# function on varying range of data-types
# importing statistics module
from statistics import variance
# importing fractions as parameter values
from fractions import Fraction as fr
# tuple of a set of positive integers
# numbers are spread apart but not very much
sample1 = (1, 2, 5, 4, 8, 9, 12)
# tuple of a set of negative integers
sample2 = (-2, -4, -3, -1, -5, -6)
# tuple of a set of positive and negative numbers
# data-points are spread apart considerably 
sample3 = (-9, -1, -0, 2, 1, 3, 4, 19)
# tuple of a set of fractional numbers
sample4 = (fr(1, 2), fr(2, 3), fr(3, 4),
                     fr(5, 6), fr(7, 8))
# tuple of a set of floating point values
sample5 = (1.23, 1.45, 2.1, 2.2, 1.9)
# Print the variance of each samples
print("Variance of Sample1 is % s " %(variance(sample1)))
print("Variance of Sample2 is % s " %(variance(sample2)))
print("Variance of Sample3 is % s " %(variance(sample3)))
print("Variance of Sample4 is % s " %(variance(sample4)))
print("Variance of Sample5 is % s " %(variance(sample5)))
<div class="dropdown" data-bs-theme="light">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButtonLight" data-bs-toggle="dropdown" aria-expanded="false">
    Default dropdown
  </button>
  <ul class="dropdown-menu" aria-labelledby="dropdownMenuButtonLight">
    <li><a class="dropdown-item active" href="#">Action</a></li>
    <li><a class="dropdown-item" href="#">Action</a></li>
    <li><a class="dropdown-item" href="#">Another action</a></li>
    <li><a class="dropdown-item" href="#">Something else here</a></li>
    <li><hr class="dropdown-divider"></li>
    <li><a class="dropdown-item" href="#">Separated link</a></li>
  </ul>
</div>
<div class="dropdown" data-bs-theme="dark">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButtonDark" data-bs-toggle="dropdown" aria-expanded="false">
    Dark dropdown
  </button>
  <ul class="dropdown-menu" aria-labelledby="dropdownMenuButtonDark">
    <li><a class="dropdown-item active" href="#">Action</a></li>
    <li><a class="dropdown-item" href="#">Action</a></li>
    <li><a class="dropdown-item" href="#">Another action</a></li>
    <li><a class="dropdown-item" href="#">Something else here</a></li>
    <li><hr class="dropdown-divider"></li>
    <li><a class="dropdown-item" href="#">Separated link</a></li>
  </ul>
</div>
<div class="form-floating">
  <select class="form-select" id="floatingSelect" aria-label="Floating label select example">
    <option selected>Open this select menu</option>
    <option value="1">One</option>
    <option value="2">Two</option>
    <option value="3">Three</option>
  </select>
  <label for="floatingSelect">Works with selects</label>
</div>
<div class="form-floating mb-3">
  <input type="email" class="form-control" id="floatingInputDisabled" placeholder="name@example.com" disabled>
  <label for="floatingInputDisabled">Email address</label>
</div>
<div class="form-floating mb-3">
  <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextareaDisabled" disabled></textarea>
  <label for="floatingTextareaDisabled">Comments</label>
</div>
<div class="form-floating mb-3">
  <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2Disabled" style="height: 100px" disabled>Disabled textarea with some text inside</textarea>
  <label for="floatingTextarea2Disabled">Comments</label>
</div>
<div class="form-floating">
  <select class="form-select" id="floatingSelectDisabled" aria-label="Floating label disabled select example" disabled>
    <option selected>Open this select menu</option>
    <option value="1">One</option>
    <option value="2">Two</option>
    <option value="3">Three</option>
  </select>
  <label for="floatingSelectDisabled">Works with selects</label>
</div
<table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
<!-- On tables -->
<table class="table-primary">...</table>
<table class="table-secondary">...</table>
<table class="table-success">...</table>
<table class="table-danger">...</table>
<table class="table-warning">...</table>
<table class="table-info">...</table>
<table class="table-light">...</table>
<table class="table-dark">...</table>
<!-- On rows -->
<tr class="table-primary">...</tr>
<tr class="table-secondary">...</tr>
<tr class="table-success">...</tr>
<tr class="table-danger">...</tr>
<tr class="table-warning">...</tr>
<tr class="table-info">...</tr>
<tr class="table-light">...</tr>
<tr class="table-dark">...</tr>
<!-- On cells (`td` or `th`) -->
<tr>
  <td class="table-primary">...</td>
  <td class="table-secondary">...</td>
  <td class="table-success">...</td>
  <td class="table-danger">...</td>
  <td class="table-warning">...</td>
  <td class="table-info">...</td>
  <td class="table-light">...</td>
  <td class="table-dark">...</td>
</tr>
<table class="table">
  <thead>
    ...
  </thead>
  <tbody>
    <tr class="table-active">
      ...
    </tr>
    <tr>
      ...
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2" class="table-active">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
<table class="table table-dark">
  <thead>
    ...
  </thead>
  <tbody>
    <tr class="table-active">
      ...
    </tr>
    <tr>
      ...
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2" class="table-active">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
@mixin table-variant($state, $background) {
  .table-#{$state} {
    $color: color-contrast(opaque($body-bg, $background));
    $hover-bg: mix($color, $background, percentage($table-hover-bg-factor));
    $striped-bg: mix($color, $background, percentage($table-striped-bg-factor));
    $active-bg: mix($color, $background, percentage($table-active-bg-factor));
    $table-border-color: mix($color, $background, percentage($table-border-factor));
    --#{$prefix}table-color: #{$color};
    --#{$prefix}table-bg: #{$background};
    --#{$prefix}table-border-color: #{$table-border-color};
    --#{$prefix}table-striped-bg: #{$striped-bg};
    --#{$prefix}table-striped-color: #{color-contrast($striped-bg)};
    --#{$prefix}table-active-bg: #{$active-bg};
    --#{$prefix}table-active-color: #{color-contrast($active-bg)};
    --#{$prefix}table-hover-bg: #{$hover-bg};
    --#{$prefix}table-hover-color: #{color-contrast($hover-bg)};
    color: var(--#{$prefix}table-color);
    border-color: var(--#{$prefix}table-border-color);
  }
}
<table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody class="table-group-divider">
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
<div class="table-responsive">
  <table class="table align-middle">
    <thead>
      <tr>
        ...
      </tr>
    </thead>
    <tbody>
      <tr>
        ...
      </tr>
      <tr class="align-bottom">
        ...
      </tr>
      <tr>
        <td>...</td>
        <td>...</td>
        <td class="align-top">This cell is aligned to the top.</td>
        <td>...</td>
      </tr>
    </tbody>
  </table>
</div>
<table class="table table-striped table-bordered">
  <thead>
    ...
  </thead>
  <tbody>
    ...
    <tr>
      <td colspan="4">
        <table class="table mb-0">
          ...
        </table>
      </td>
    </tr>
    ...
  </tbody>
</table>
<table class="table caption-top">
  <caption>List of users</caption>
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
<div class="table-responsive">
  <table class="table">
    ...
  </table>
</div>
<div class="table-responsive-sm">
  <table class="table">
    ...
  </table>
</div>
<div class="table-responsive-md">
  <table class="table">
    ...
  </table>
</div>
<div class="table-responsive-lg">
  <table class="table">
    ...
  </table>
</div>
<div class="table-responsive-xl">
  <table class="table">
    ...
  </table>
</div>
<div class="table-responsive-xxl">
  <table class="table">
    ...
  </table>
</div>
$table-cell-padding-y:        .5rem;
$table-cell-padding-x:        .5rem;
$table-cell-padding-y-sm:     .25rem;
$table-cell-padding-x-sm:     .25rem;
$table-cell-vertical-align:   top;
$table-color:                 var(--#{$prefix}emphasis-color);
$table-bg:                    var(--#{$prefix}body-bg);
$table-accent-bg:             transparent;
$table-th-font-weight:        null;
$table-striped-color:         $table-color;
$table-striped-bg-factor:     .05;
$table-striped-bg:            rgba(var(--#{$prefix}emphasis-color-rgb), $table-striped-bg-factor);
$table-active-color:          $table-color;
$table-active-bg-factor:      .1;
$table-active-bg:             rgba(var(--#{$prefix}emphasis-color-rgb), $table-active-bg-factor);
$table-hover-color:           $table-color;
$table-hover-bg-factor:       .075;
$table-hover-bg:              rgba(var(--#{$prefix}emphasis-color-rgb), $table-hover-bg-factor);
$table-border-factor:         .2;
$table-border-width:          var(--#{$prefix}border-width);
$table-border-color:          var(--#{$prefix}border-color);
$table-striped-order:         odd;
$table-striped-columns-order: even;
$table-group-separator-color: currentcolor;
$table-caption-color:         var(--#{$prefix}secondary-color);
$table-bg-scale:              -80%;
$table-variants: (
  "primary":    shift-color($primary, $table-bg-scale),
  "secondary":  shift-color($secondary, $table-bg-scale),
  "success":    shift-color($success, $table-bg-scale),
  "info":       shift-color($info, $table-bg-scale),
  "warning":    shift-color($warning, $table-bg-scale),
  "danger":     shift-color($danger, $table-bg-scale),
  "light":      $light,
  "dark":       $dark,);
  <form>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
<form>
  <fieldset disabled>
    <legend>Disabled fieldset example</legend>
    <div class="mb-3">
      <label for="disabledTextInput" class="form-label">Disabled input</label>
      <input type="text" id="disabledTextInput" class="form-control" placeholder="Disabled input">
    </div>
    <div class="mb-3">
      <label for="disabledSelect" class="form-label">Disabled select menu</label>
      <select id="disabledSelect" class="form-select">
        <option>Disabled select</option>
      </select>
    </div>
    <div class="mb-3">
      <div class="form-check">
        <input class="form-check-input" type="checkbox" id="disabledFieldsetCheck" disabled>
        <label class="form-check-label" for="disabledFieldsetCheck">
          Can't check this
        </label>
      </div>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </fieldset>
</form>
$input-btn-padding-y:         .375rem;
$input-btn-padding-x:         .75rem;
$input-btn-font-family:       null;
$input-btn-font-size:         $font-size-base;
$input-btn-line-height:       $line-height-base;
$input-btn-focus-width:         $focus-ring-width;
$input-btn-focus-color-opacity: $focus-ring-opacity;
$input-btn-focus-color:         $focus-ring-color;
$input-btn-focus-blur:          $focus-ring-blur;
$input-btn-focus-box-shadow:    $focus-ring-box-shadow;

$input-btn-padding-y-sm:      .25rem;
$input-btn-padding-x-sm:      .5rem;
$input-btn-font-size-sm:      $font-size-sm;

$input-btn-padding-y-lg:      .5rem;
$input-btn-padding-x-lg:      1rem;
$input-btn-font-size-lg:      $font-size-lg;

$input-btn-border-width:      var(--#{$prefix}border-width);
<div class="row g-3 align-items-center">
  <div class="col-auto">
    <label for="inputPassword6" class="col-form-label">Password</label>
  </div>
  <div class="col-auto">
    <input type="password" id="inputPassword6" class="form-control" aria-describedby="passwordHelpInline">
  </div>
  <div class="col-auto">
    <span id="passwordHelpInline" class="form-text">
      Must be 8-20 characters long.
    </span>
  </div>
</div>
<form class="row g-3">
  <div class="col-auto">
    <label for="staticEmail2" class="visually-hidden">Email</label>
    <input type="text" readonly class="form-control-plaintext" id="staticEmail2" value="email@example.com">
  </div>
  <div class="col-auto">
    <label for="inputPassword2" class="visually-hidden">Password</label>
    <input type="password" class="form-control" id="inputPassword2" placeholder="Password">
  </div>
  <div class="col-auto">
    <button type="submit" class="btn btn-primary mb-3">Confirm identity</button>
  </div>
</form>
<div class="mb-3">
  <label for="formFile" class="form-label">Default file input example</label>
  <input class="form-control" type="file" id="formFile">
</div>
<div class="mb-3">
  <label for="formFileMultiple" class="form-label">Multiple files input example</label>
  <input class="form-control" type="file" id="formFileMultiple" multiple>
</div>
<div class="mb-3">
  <label for="formFileDisabled" class="form-label">Disabled file input example</label>
  <input class="form-control" type="file" id="formFileDisabled" disabled>
</div>
<div class="mb-3">
  <label for="formFileSm" class="form-label">Small file input example</label>
  <input class="form-control form-control-sm" id="formFileSm" type="file">
</div>
<div>
  <label for="formFileLg" class="form-label">Large file input example</label>
  <input class="form-control form-control-lg" id="formFileLg" type="file">
</div>
$input-padding-y:                       $input-btn-padding-y;
$input-padding-x:                       $input-btn-padding-x;
$input-font-family:                     $input-btn-font-family;
$input-font-size:                       $input-btn-font-size;
$input-font-weight:                     $font-weight-base;
$input-line-height:                     $input-btn-line-height;

$input-padding-y-sm:                    $input-btn-padding-y-sm;
$input-padding-x-sm:                    $input-btn-padding-x-sm;
$input-font-size-sm:                    $input-btn-font-size-sm;

$input-padding-y-lg:                    $input-btn-padding-y-lg;
$input-padding-x-lg:                    $input-btn-padding-x-lg;
$input-font-size-lg:                    $input-btn-font-size-lg;

$input-bg:                              var(--#{$prefix}body-bg);
$input-disabled-color:                  null;
$input-disabled-bg:                     var(--#{$prefix}secondary-bg);
$input-disabled-border-color:           null;

$input-color:                           var(--#{$prefix}body-color);
$input-border-color:                    var(--#{$prefix}border-color);
$input-border-width:                    $input-btn-border-width;
$input-box-shadow:                      var(--#{$prefix}box-shadow-inset);

$input-border-radius:                   var(--#{$prefix}border-radius);
$input-border-radius-sm:                var(--#{$prefix}border-radius-sm);
$input-border-radius-lg:                var(--#{$prefix}border-radius-lg);

$input-focus-bg:                        $input-bg;
$input-focus-border-color:              tint-color($component-active-bg, 50%);
$input-focus-color:                     $input-color;
$input-focus-width:                     $input-btn-focus-width;
$input-focus-box-shadow:                $input-btn-focus-box-shadow;

$input-placeholder-color:               var(--#{$prefix}secondary-color);
$input-plaintext-color:                 var(--#{$prefix}body-color);

$input-height-border:                   calc(#{$input-border-width} * 2); // stylelint-disable-line function-disallowed-list

$input-height-inner:                    add($input-line-height * 1em, $input-padding-y * 2);
$input-height-inner-half:               add($input-line-height * .5em, $input-padding-y);
$input-height-inner-quarter:            add($input-line-height * .25em, $input-padding-y * .5);

$input-height:                          add($input-line-height * 1em, add($input-padding-y * 2, $input-height-border, false));
$input-height-sm:                       add($input-line-height * 1em, add($input-padding-y-sm * 2, $input-height-border, false));
$input-height-lg:                       add($input-line-height * 1em, add($input-padding-y-lg * 2, $input-height-border, false));

$input-transition:                      border-color .15s ease-in-out, box-shadow .15s ease-in-out;

$form-color-width:                      3rem;
# https://github.com/browserslist/browserslist#readme

>= 0.5%
last 2 major versions
not dead
Chrome >= 60
Firefox >= 60
Firefox ESR
iOS >= 12
Safari >= 12
not Explorer <= 11>
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <title>Hello, modularity!</title>
  </head>
  <body>
    <h1>Hello, modularity!</h1>
    <button id="popoverButton" type="button" class="btn btn-primary btn-lg" data-bs-toggle="popover" title="ESM in Browser" data-bs-content="Bang!">Custom popover</button>

    <script async src="https://cdn.jsdelivr.net/npm/es-module-shims@1/dist/es-module-shims.min.js" crossorigin="anonymous"></script>
    <script type="importmap">
    {
      "imports": {
        "@popperjs/core": "https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/esm/popper.min.js",
        "bootstrap": "https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.esm.min.js"
      }
    }
    </script>
    <script type="module">
      import * as bootstrap from 'bootstrap'

      new bootstrap.Popover(document.getElementById('popoverButton'))
    </script>
  </body>
</html>
const myCarouselEl = document.querySelector('#myCarousel')
const carousel = bootstrap.Carousel.getInstance(myCarouselEl) // Retrieve a Carousel instance

myCarouselEl.addEventListener('slid.bs.carousel', event => {
  carousel.to('2') // Will slide to the slide 2 as soon as the transition to slide 1 is finished
})

carousel.to('1') // Will start sliding to the slide 1 and returns to the caller
carousel.to('2') // !! Will be ignored, as the transition to the slide 1 is not finished !!
const ARIA_ATTRIBUTE_PATTERN = /^aria-[\w-]*$/i

export const DefaultAllowlist = {
  // Global attributes allowed on any supplied element below.
  '*': ['class', 'dir', 'id', 'lang', 'role', ARIA_ATTRIBUTE_PATTERN],
  a: ['target', 'href', 'title', 'rel'],
  area: [],
  b: [],
  br: [],
  col: [],
  code: [],
  dd: [],
  div: [],
  dl: [],
  dt: [],
  em: [],
  hr: [],
  h1: [],
  h2: [],
  h3: [],
  h4: [],
  h5: [],
  h6: [],
  i: [],
  img: ['src', 'srcset', 'alt', 'title', 'width', 'height'],
  li: [],
  ol: [],
  p: [],
  pre: [],
  s: [],
  small: [],
  span: [],
  sub: [],
  sup: [],
  strong: [],
  u: [],
  ul: []
}
<div class="grid text-center">
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
  <div>1</div>
</div>
<div class="grid text-center" style="--bs-columns: 3;">
  <div>
    First auto-column
    <div class="grid">
      <div>Auto-column</div>
      <div>Auto-column</div>
    </div>
  </div>
  <div>
    Second auto-column
    <div class="grid" style="--bs-columns: 12;">
      <div class="g-col-6">6 of 12</div>
      <div class="g-col-4">4 of 12</div>
      <div class="g-col-2">2 of 12</div>
    </div>
  </div>
  <div>Third auto-column</div>
</div>
@if $font-size-root != null {
  --#{$prefix}root-font-size: #{$font-size-root};
}
--#{$prefix}body-font-family: #{inspect($font-family-base)};
@include rfs($font-size-base, --#{$prefix}body-font-size);
--#{$prefix}body-font-weight: #{$font-weight-base};
--#{$prefix}body-line-height: #{$line-height-base};
@if $body-text-align != null {
  --#{$prefix}body-text-align: #{$body-text-align};
}

--#{$prefix}body-color: #{$body-color};
--#{$prefix}body-color-rgb: #{to-rgb($body-color)};
--#{$prefix}body-bg: #{$body-bg};
--#{$prefix}body-bg-rgb: #{to-rgb($body-bg)};

--#{$prefix}emphasis-color: #{$body-emphasis-color};
--#{$prefix}emphasis-color-rgb: #{to-rgb($body-emphasis-color)};

--#{$prefix}secondary-color: #{$body-secondary-color};
--#{$prefix}secondary-color-rgb: #{to-rgb($body-secondary-color)};
--#{$prefix}secondary-bg: #{$body-secondary-bg};
--#{$prefix}secondary-bg-rgb: #{to-rgb($body-secondary-bg)};

--#{$prefix}tertiary-color: #{$body-tertiary-color};
--#{$prefix}tertiary-color-rgb: #{to-rgb($body-tertiary-color)};
--#{$prefix}tertiary-bg: #{$body-tertiary-bg};
--#{$prefix}tertiary-bg-rgb: #{to-rgb($body-tertiary-bg)};
body {
  margin: 0; // 1
  font-family: var(--#{$prefix}body-font-family);
  @include font-size(var(--#{$prefix}body-font-size));
  font-weight: var(--#{$prefix}body-font-weight);
  line-height: var(--#{$prefix}body-line-height);
  color: var(--#{$prefix}body-color);
  text-align: var(--#{$prefix}body-text-align);
  background-color: var(--#{$prefix}body-bg); // 2
  -webkit-text-size-adjust: 100%; // 3
  -webkit-tap-highlight-color: rgba($black, 0); // 4
}
$font-family-sans-serif:
  // Cross-platform generic font family (default user interface font)
  system-ui,
  // Safari for macOS and iOS (San Francisco)
  -apple-system,
  // Windows
  "Segoe UI",
  // Android
  Roboto,
  // older macOS and iOS
  "Helvetica Neue",
  // Linux
  "Noto Sans",
  "Liberation Sans",
  // Basic web fallback
  Arial,
  // Sans serif fallback
  sans-serif,
  // Emoji fonts
  "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji" !default;****
  <table>
  <caption>
    This is an example table, and this is its caption to describe the contents.
  </caption>
  <thead>
    <tr>
      <th>Table heading</th>
      <th>Table heading</th>
      <th>Table heading</th>
      <th>Table heading</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Table cell</td>
      <td>Table cell</td>
      <td>Table cell</td>
      <td>Table cell</td>
    </tr>
    <tr>
      <td>Table cell</td>
      <td>Table cell</td>
      <td>Table cell</td>
      <td>Table cell</td>
    </tr>
    <tr>
      <td>Table cell</td>
      <td>Table cell</td>
      <td>Table cell</td>
      <td>Table cell</td>
    </tr>
  </tbody>
</table>
<p>You can use the mark tag to <mark>highlight</mark> text.</p>
<p><del>This line of text is meant to be treated as deleted text.</del></p>
<p><s>This line of text is meant to be treated as no longer accurate.</s></p>
<p><ins>This line of text is meant to be treated as an addition to the document.</ins></p>
<p><u>This line of text will render as underlined.</u></p>
<p><small>This line of text is meant to be treated as fine print.</small></p>
<p><strong>This line rendered as bold text.</strong></p>
<p><em>This line rendered as italicized text.</em></p>
<dl class="row">
  <dt class="col-sm-3">Description lists</dt>
  <dd class="col-sm-9">A description list is perfect for defining terms.</dd>

  <dt class="col-sm-3">Term</dt>
  <dd class="col-sm-9">
    <p>Definition for the term.</p>
    <p>And some more placeholder definition text.</p>
  </dd>

  <dt class="col-sm-3">Another term</dt>
  <dd class="col-sm-9">This definition is short, so no extra paragraphs or anything.</dd>

  <dt class="col-sm-3 text-truncate">Truncated term is truncated</dt>
  <dd class="col-sm-9">This can be useful when space is tight. Adds an ellipsis at the end.</dd>

  <dt class="col-sm-3">Nesting</dt>
  <dd class="col-sm-9">
    <dl class="row">
      <dt class="col-sm-4">Nested definition list</dt>
      <dd class="col-sm-8">I heard you like definition lists. Let me put a definition list inside your definition list.</dd>
    </dl>
  </dd>
</dl>
<table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
<!-- On tables -->
<table class="table-primary">...</table>
<table class="table-secondary">...</table>
<table class="table-success">...</table>
<table class="table-danger">...</table>
<table class="table-warning">...</table>
<table class="table-info">...</table>
<table class="table-light">...</table>
<table class="table-dark">...</table>

<!-- On rows -->
<tr class="table-primary">...</tr>
<tr class="table-secondary">...</tr>
<tr class="table-success">...</tr>
<tr class="table-danger">...</tr>
<tr class="table-warning">...</tr>
<tr class="table-info">...</tr>
<tr class="table-light">...</tr>
<tr class="table-dark">...</tr>

<!-- On cells (`td` or `th`) -->
<tr>
  <td class="table-primary">...</td>
  <td class="table-secondary">...</td>
  <td class="table-success">...</td>
  <td class="table-danger">...</td>
  <td class="table-warning">...</td>
  <td class="table-info">...</td>
  <td class="table-light">...</td>
  <td class="table-dark">...</td>
</tr>
<table class="table">
  <thead>
    ...
  </thead>
  <tbody>
    <tr class="table-active">
      ...
    </tr>
    <tr>
      ...
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2" class="table-active">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
<table class="table table-dark">
  <thead>
    ...
  </thead>
  <tbody>
    <tr class="table-active">
      ...
    </tr>
    <tr>
      ...
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2" class="table-active">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
@mixin table-variant($state, $background) {
  .table-#{$state} {
    $color: color-contrast(opaque($body-bg, $background));
    $hover-bg: mix($color, $background, percentage($table-hover-bg-factor));
    $striped-bg: mix($color, $background, percentage($table-striped-bg-factor));
    $active-bg: mix($color, $background, percentage($table-active-bg-factor));
    $table-border-color: mix($color, $background, percentage($table-border-factor));

    --#{$prefix}table-color: #{$color};
    --#{$prefix}table-bg: #{$background};
    --#{$prefix}table-border-color: #{$table-border-color};
    --#{$prefix}table-striped-bg: #{$striped-bg};
    --#{$prefix}table-striped-color: #{color-contrast($striped-bg)};
    --#{$prefix}table-active-bg: #{$active-bg};
    --#{$prefix}table-active-color: #{color-contrast($active-bg)};
    --#{$prefix}table-hover-bg: #{$hover-bg};
    --#{$prefix}table-hover-color: #{color-contrast($hover-bg)};

    color: var(--#{$prefix}table-color);
    border-color: var(--#{$prefix}table-border-color);
  }
}
<table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody class="table-group-divider">
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
<div class="table-responsive">
  <table class="table align-middle">
    <thead>
      <tr>
        ...
      </tr>
    </thead>
    <tbody>
      <tr>
        ...
      </tr>
      <tr class="align-bottom">
        ...
      </tr>
      <tr>
        <td>...</td>
        <td>...</td>
        <td class="align-top">This cell is aligned to the top.</td>
        <td>...</td>
      </tr>
    </tbody>
  </table>
</div>
