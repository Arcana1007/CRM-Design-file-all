<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Customers</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha512-SfTiTlX6kk+qitfevl/7LibUOeJWlt9rbyDn92a1DqWOw9vWG2MFoays0sgObmWazO5BQPiFucnnEAjpAB+/Sw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="assets/css/style.css">
    <link rel="stylesheet" type="text/css" href="assets/css/customer.css">
    <link rel="stylesheet" href="css/bootsrap.min.css">
   
  </head>
  <body>
  
 <!-- navbar -->
 <nav class="navbar navbar-dark bg-dark navbar-expand-sm p-0">
    <a class="navbar-brand bg-white p-2" href="#">
        <img class="logo" src="https://www.livekeeping.com/assets/web_images/livekeeping-indiamart.svg" width="170" height="50" alt="logo">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar-list-2" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse p-2" id="navbar-list-2">
        <ul class="navbar-nav ">
            <li class="nav-item ">
                <a class="nav-link" href="#">Start Calling<span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item dashboard">
                <a class="nav-link" href="#">Dashboard</a>
            </li>
            <li class="nav-item customer active">
                <a class="nav-link" href="#">Customers</a>
            </li>
            <li class="nav-item report">
                <a class="nav-link" href="#">Reports</a>
            </li>
            <li class="nav-item search">
                <div class="form-group has-search mb-0">
                    <span class="fa fa-search form-control-feedback"></span>
                    <input size="40" type="text" class="form-control" placeholder="Search Customer by name, phone, ID">
                </div>
            </li>
            <li class="nav-item dropdown">
                <a class="dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
                    Nisha K
                </a>
                <div class="dropdown-menu">
                    <a class="dropdown-item" href="#">Link 1</a>
                    <a class="dropdown-item" href="#">Link 2</a>
                    <a class="dropdown-item" href="#">Link 3</a>
                </div>
            </li> 
        </ul>
    </div>
</nav>
<!-- sidebar -->
    <div class="container-fluid">
        <div class="row">
          <div class=" collapse d-md-flex bg-light pt-3 min-vh-100  " id="sidebar">
            <ul class="nav flex-column flex-nowrap ">
              <li class="nav-item">
                <div class="d-flex justify-content-between py-3 ">
                      <div style="width: 100%;">
                        <input type="radio" id="test1" name="radio-group">
                        <label for="test1" class="sidebar_main_text">All Customers</label>
                      </div>
                      <span>(56)</span>
                </div>
                </li>
                <div class="space"></div>

              <li class="nav-item">
                <h6>For Installation</h6>
                    <hr>
                    <div class="d-flex justify-content-between py-3 ">
                      <div style="width: 90%;">
                        <input type="radio" id="test2" name="radio-group1">
                        <label for="test2" class="sidebar_main_text">Open Hot leads</label>
                      </div>
                      <span>(56)</span>
                </div>


                <div class="d-flex align-items-center">
                <a class="nav-link collapsed dropdownicon" href="#submenu1" data-toggle="collapse" data-target="#submenu1"></a><h6>My Reminders</h6></div>
                <div class="collapse" id="submenu1" aria-expanded="false">
                  <ul class="flex-column nav">
                              <li class="nav-item">
                                <div class="d-flex justify-content-between py-3 ">
                                <div style="width: 90%;">
                                  <input type="radio" id="test3" name="radio-group2">
                                  <label for="test3">Open Hot leads</label>
                                </div>
                                <span>(56)</span>
                          </div></li>

                          <li class="nav-item">
                            <div class="d-flex justify-content-between py-3 ">
                            <div style="width: 90%;">
                              <input type="radio" id="test4" name="radio-group2">
                              <label for="test4">Talked</label>
                            </div>
                            <span>(56)</span>
                      </div></li>

                      <li class="nav-item">
                        <div class="d-flex justify-content-between py-3 ">
                        <div style="width: 90%;">
                          <input type="radio" id="test5" name="radio-group2">
                          <label for="test5">Not responding</label>
                        </div>
                        <span>(56)</span></div></li>
                  </ul></div>

                  <hr class="w-100">
                <li class="nav-item">
                  <div class="d-flex justify-content-between py-3 ">
                        <div style="width: 90%;">
                          <input type="radio" id="test6" name="radio-group3">
                          <label for="test6" class="sidebar_main_text">Untouched leads</label>
                        </div>
                        <span>(56)</span>
                  </div>
                  </li>
                  <div class="space"></div>
              <li class="nav-item">
                <h6>For Payment</h6>
                    <hr class="w-100">
                    <div class="d-flex justify-content-between py-3 ">
                      <div style="width: 90%;">
                        <input type="radio" id="test7" name="radio-group4">
                        <label for="test7"class="sidebar_main_text">Open Trials</label>
                      </div>
                      <span>(56)</span>
                </div>
                <div class="d-flex align-items-center">
                  <a class="nav-link collapsed dropdownicon" href="#submenu2" data-toggle="collapse" data-target="#submenu2"></a><h6>My Reminders</h6> </div>
                  <div class="collapse" id="submenu2" aria-expanded="false">
                    <ul class="flex-column nav">
                                <li class="nav-item">
                                  <div class="d-flex justify-content-between py-3">
                                  <div style="width: 90%;">
                                    <input type="radio" id="test8" name="radio-group5">
                                    <label for="test8">Open Hot leads</label>
                                  </div>
                                  <span>(56)</span>
                            </div></li>
  
                            <li class="nav-item">
                              <div class="d-flex justify-content-between py-3">
                              <div style="width: 90%;">
                                <input type="radio" id="test9" name="radio-group5">
                                <label for="test9">Talked</label>
                              </div>
                              <span>(56)</span>
                        </div></li>
  
                        <li class="nav-item">
                          <div class="d-flex justify-content-between py-3">
                          <div style="width: 90%;">
                            <input type="radio" id="test10" name="radio-group5">
                            <label for="test10">Not responding</label>
                          </div>
                          <span>(56)</span></div></li>
                    </ul></div>
              
            </ul>
           </div>
        
          <div class="col pt-3">
            <div class="container-fluid d-flex justify-content-between align-items-center">
                <h4>
                <a href="" data-target="#sidebar" data-toggle="collapse" class="d-md-none"><i class="fa fa-bars"></i></a> Customers
              </h4>
              <div class="form-check">
                <input class="form-check-input" type="checkbox" value="" id="flexCheckChecked" checked>
                <label class="form-check-label" for="flexCheckChecked">
                    Trial extended
                </label>
              </div>
            </div>
            
           
<table class="table table-striped  customer-details mt-2">
                <tr class="head">
                <th>Name</th>
                <th>ID</th>
                <th>Next reminder</th>
                <th>Follow up Status</th>
                <th>Tally</th>
                <th>Last connect</th>
                <th>Customer status</th>
                <th>Notes</th>
                <th> </th>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no1" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >yes</td>
                <td>15th Mar ’23.</td>
                <td>Free</td>
                <td>Lorem ipsum...</td>
                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no2" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem ipsum...</td>
                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no3" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem ipsum...</td>
                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no4" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem ipsum...</td>
                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no5" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem ipsum...</td>
                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no6" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem ipsum...</td>
                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no7" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem ipsum...</td>
                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no8" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem ipsum...</td>


                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no9" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem ipsum...</td>
                <td></td>
                </tr>
                <tr>
                <td class="customer_id"><a id="customer-no10" href="#">Raj Kothari</a></td>
                <td >C-000340</td>
                <td >28th Mar'23 10:00AM</td>
                <td >Talked</td>
                <td >Yes</td>
                <td>15th Mar ’23.</td>
                <td>FREE</td>
                <td>Lorem Ipsum...</td>
                <td></td>
                </tr>
                   
            </table>
            <!-- pagination -->

      <div class="container-fluid d-flex justify-content-between ">
        <span class="pages">1-10 of 10</span>
          <div class="d-inline-block">
              <ul style="list-style: none;" class="d-inline-block justify-content-center pr-2">
                    <li class="nav-item dropdown d-inline-block pr-2 mr-0">
                        <a class="dropdown-toggle perpages" href="#" id="navbardrop" data-toggle="dropdown">
                            Rows per page 10
                        </a> 
                        <div class="dropdown-menu">
                            <a class="dropdown-item" href="#">15</a>
                            <a class="dropdown-item" href="#">20</a>
                            <a class="dropdown-item" href="#">25</a>
                        </div>
                    </li>
                </ul>
                <a class="arrow mr-2" href=""><i class="fa fa-chevron-left" aria-hidden="true"></i></a>
                <span class="page-no">1</span>
                <a class="arrow ml-2" href=""><i class="fa fa-chevron-right" aria-hidden="true"></i></i></a>
          </div>
      </div>
          </div>
        </div>
      </div>
      <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
      <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>


   
  </body>
</html>
