
<!DOCTYPE html>
<html>


    <!-- Mirrored from webapplayers.com/inspinia_admin-v2.1/dashboard_2.html by HTTrack Website Copier/3.x [XR&CO'2013], Sun, 31 May 2015 10:00:34 GMT -->
    <head>

        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <title>SdevTeam School Management System | Dashboard</title>

        <meta name="keywords" content="school, management, system, software, academic"/>
        <meta name="description" content="Sdev School Management System a clean and modern school management system that covers everything from exams and
                    assignments to budgeting and internal messaging for all staff. Appsource SMS has a ton
                    of features that largely appeal to teachers. It�s built with a complete suite of applications that permits
                    you to automate all aspects of a school, including student information system, student-grading,
                    student billing & library management."/>

        <link href="css/bootstrap.min.css" rel="stylesheet">
        <link href="font-awesome/css/font-awesome.css" rel="stylesheet">

        <!-- Morris -->
        <link href="css/plugins/morris/morris-0.4.3.min.css" rel="stylesheet">

        <!-- Gritter -->
        <link href="js/plugins/gritter/jquery.gritter.css" rel="stylesheet">

        <link href="css/animate.css" rel="stylesheet">
        <link href="css/style.css" rel="stylesheet">

    </head>

    <body>
        <div id="wrapper">
            <nav class="navbar-default navbar-static-side" role="navigation">
                <div class="sidebar-collapse">
    <ul class="nav" id="side-menu">
        <li class="nav-header">
            <div class="dropdown profile-element"> <span>
                    <img alt="image" class="img-circle" src="img/profile_small.jpg" />
                </span>
                <a data-toggle="dropdown" class="dropdown-toggle" href="#">
                    <span class="clear"> <span class="block m-t-xs"> <strong class="font-bold">Aditya</strong>
                        </span> <span class="text-muted text-xs block">Super User </span> </a>
                <ul class="dropdown-menu animated fadeInRight m-t-xs">
                    <li><a href="index.php?page=update_account">Profile</a></li>
                    <li class="divider"></li>
                    <li><a href="index.php?page=logout">Logout</a></li>
                </ul>
            </div>
            <div class="logo-element">

            </div>
        </li>
        <li>
            <a href="index.php?page=dashboard"><i  class="fa fa-home"></i> <span class="nav-label">Dashboard</span></a>
        </li>
 
        <!--School Settings-->
                    <li>
                <a href="#"><i class="fa fa-gear"></i> <span class="nav-label">School Settings</span><span class="fa arrow"></span></a>
                <ul class="nav nav-second-level">
                                            <li><a href="index.php?page=sch_descriptions"><i class="fa fa-caret-right"></i>School Description</a></li>
                        <li><a href="index.php?page=add_house"><i class="fa fa-caret-right"></i>Add House</a></li>
                        <li><a href="index.php?page=academic_years"><i class="fa fa-caret-right"></i>Add Year</a></li>
                        <li><a href="index.php?page=report_control"><i class="fa fa-caret-right"></i>Report Generation Control</a></li>
                                                                <li><a href="index.php?page=add_class"><i class="fa fa-caret-right"></i>Add Classes</a></li>
                        <li><a href="index.php?page=add_stream"><i class="fa fa-caret-right"></i>Add Streams</a></li>
                        <li><a href="index.php?page=add_term"><i class="fa fa-caret-right"></i>Add Terms</a></li>
                        <li><a href="index.php?page=add_o_level_subject"><i class="fa fa-caret-right"></i>Add O-Level Subjects</a></li>
                        <li><a href="index.php?page=add_a_level_subject"><i class="fa fa-caret-right"></i>Add A-Level Subjects</a></li>
                        <li><a href="index.php?page=add_combination"><i class="fa fa-caret-right"></i>Add Combinations</a></li>
                        <li><a href="index.php?page=add_exam_set"><i class="fa fa-caret-right"></i>Add Exam Sets</a></li>
                        <li><a href="index.php?page=add_grading_system"><i class="fa fa-caret-right"></i>Grading System</a></li>
                                    </ul>
            </li>
        
        <!--System Users-->
        <li>
            <a href="#"><i class="fa fa-users"></i> <span class="nav-label">Users</span><span class="fa arrow"></span></a>
            <ul class="nav nav-second-level">
                                    <li><a href="index.php?page=add_users"><i class="fa fa-caret-right"></i>Add User</a></li>
                    <li><a href="index.php?page=view_users"><i class="fa fa-caret-right"></i>List Users</a></li>
                                <li><a href="index.php?page=update_account"><i class="fa fa-caret-right"></i>Change Password</a></li>
                <!--<li><a href="index.php?page=update_account"><i class="fa fa-caret-right"></i>Password Recovery</a></li>-->
            </ul>
        </li>
        <!--Teachers-->
        
        <!--Students-->
                    <li>
                <a href="#"><i class="fa fa-user-md"></i> <span class="nav-label">Students</span><span class="fa arrow"></span></a>
                <ul class="nav nav-second-level">
                                            <li><a href="index.php?page=add_students"><i class="fa fa-caret-right"></i>Register</a></li>
                                                    <li><a href="index.php?page=view_enrollment"><i class="fa fa-caret-right"></i>View Enrollment</a></li>
                                                                </ul>
            </li>
        
        <!--Classes-->
        
        <!--Marks-->
                    <li>
                <a href="#"><i class="fa fa-bars"></i> <span class="nav-label">Marks<span class="label label-info" style="margin-left: 10px">Data</span></span><span class="fa arrow"></span></a>
                <ul class="nav nav-second-level">
                                        <li><a href=""><i class="fa fa-caret-right"></i>View Marks</a></li>
                    <li><a href=""><i class="fa fa-caret-right"></i>Mark Summary</a></li>
                    <li><a href="index.php?page=individual_marksheet"><i class="fa fa-caret-right"></i>Individual Marksheets</a></li>
                                            <li><a href="index.php?page=general_marksheet"><i class="fa fa-caret-right"></i>General Marksheets</a></li>
                                    </ul>
            </li>
        
        <!--Cards-->
                    <li>
                <a href="#"><i class="fa fa-bar-chart"></i> <span class="nav-label">Cards</span><span class="fa arrow"></span></a>
                <ul class="nav nav-second-level">
                    <li><a href="index.php?page=report_cards"><i class="fa fa-caret-right"></i>Report Cards</a></li>
                    <li><a href="index.php?page=exam_set_standings"><i class="fa fa-caret-right"></i>Exam Set Standings</a></li>
                </ul>
            </li>
        
        <!--Subjects-->
                    <li>
                <a href="#"><i class="fa fa-bar-chart"></i> <span class="nav-label">Subjects</span><span class="fa arrow"></span></a>
                <ul class="nav nav-second-level">
                                            <li><a href="index.php?page=registered_subjects"><i class="fa fa-caret-right"></i>Registered Subjects</a></li>
                        <li><a href="index.php?page=view_class_teachers"><i class="fa fa-caret-right"></i>Class Teachers</a></li>
                                                        </ul>
            </li>
        
        <!--Announcements-->
                    <li>
                <a href="#"><i class="fa fa-newspaper-o"></i> <span class="nav-label">Announcements</span><span class="fa arrow"></span></a>
                <ul class="nav nav-second-level">
                    <li><a href="index.php?page=add_announcements"><i class="fa fa-caret-right"></i>Post Announcement</a></li>
                    <li><a href="index.php?page=add_announcements"><i class="fa fa-caret-right"></i>Manage Announcements</a></li>
                </ul>
            </li>
        
        <!--Library-->
                    <li>
                <a href="#"><i class="fa fa-book"></i> <span class="nav-label">Library</span><span class="fa arrow"></span></a>
                <ul class="nav nav-second-level">
                    <!--Links for the library here-->
                    <li><a href="index.php?page=book_type"><i class="fa fa-caret-right"></i>Register Book Type</a></li>
                    <li><a href="index.php?page=register_book"><i class="fa fa-caret-right"></i>Register Book</a></li>
                    <li>
                        <a href="#"><i class="fa fa-caret-right"></i> <span class="nav-label">Manage Library</span><span class="fa arrow"></span></a>

                        <ul class="nav nav-third-level">
                            <li><a href="index.php?page=lib_students"><i class="fa fa-caret-right"></i>Lend Book</a></li>
                            <li><a href="index.php?page=av_stud_return"><i class="fa fa-caret-right"></i>Return Book</a></li>

                        </ul>
                    </li>
                    <li><a href="index.php?page=view_available_books"><i class="fa fa-book"></i>Available Books </a></li>

                </ul>
            </li>
        
        <!--Payments-->
                    <li>
                <a href="#"><i class="fa fa-paypal"></i> <span class="nav-label">Payments</span><span class="fa arrow"></span></a>
                <ul class="nav nav-second-level">
                    <!--Links for payments-->
                    <li><a href="index.php?page=view_fees_structures"><i class="fa fa-caret-right"></i>Fees Structures</a></li>
                    <li><a href="index.php?page=payment_list"><i class="fa fa-caret-right"></i>Student's Payments</a></li>
                    <li><a href="index.php?page=ledger_account"><i class="fa fa-caret-right"></i>Ledger Book</a></li>

                </ul>
            </li>
                <li >
            <a href="index.php?page=logout"><i class="fa fa-power-off"></i><span class="nav-label">Logout</span></a>
        </li>
    </ul>
</div>            </nav>
        </div>

        <div id="page-wrapper" class="gray-bg">
            <div class="row border-bottom">
                <nav class="navbar navbar-static-top" role="navigation" style="margin-bottom: 0">
    <div class="navbar-header">
        <a class="navbar-minimalize minimalize-styl-2 btn btn-primary " href="#"><i class="fa fa-bars"></i> </a>
        <form role="search" class="navbar-form-custom" action="#">
            <div class="form-group">
                <input type="text" placeholder="Search for something..." class="form-control" name="top-search" id="top-search">
            </div>
        </form>
    </div>
            <ul class="nav navbar-top-links navbar-right">
                <li>
                    <span class="m-r-sm text-muted welcome-message">Welcome to <span style="text-transform: uppercase">Scholars Den</span><b> Licensed to: SdevTeam</b></span>
                </li>
                <li class="dropdown">
                    <a class="dropdown-toggle count-info" data-toggle="dropdown" href="#">
                        <i class="fa fa-bell"></i>  <span class="label label-warning">
                            1                        </span>
                    </a>
                    <ul class="dropdown-menu dropdown-alerts">
                        <h3 style="color:blue">Announcements</h3>                        <li>
                            <div class="dropdown-messages-box">
                                <div>
                                    <small class="pull-right">11 Nov 2018</small>
                                 <small class="text-muted">3 days ago at 7:58 pm - 10.06.2014</small>
                                </div>
                            </div>
                        </li>
                        <li class="divider"></li>
                                            </ul>
                </li>
               <li class="dropdown">
                    <a class="dropdown-toggle count-info" data-toggle="dropdown" href="#">
                        <i class="fa fa-envelope"></i>  <span class="label label-primary">8</span>
                    </a>
                    <ul class="dropdown-menu dropdown-alerts">
                        <li>
                            <a href="#">
                                <div>
                                    <i class="fa fa-envelope fa-fw"></i> You have 16 messages
                                    <span class="pull-right text-muted small">4 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <i class="fa fa-twitter fa-fw"></i> 3 New Followers
                                    <span class="pull-right text-muted small">12 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="#">
                                <div>
                                    <i class="fa fa-upload fa-fw"></i> Server Rebooted
                                    <span class="pull-right text-muted small">4 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <div class="text-center link-block">
                                <a href="#">
                                    <strong>See All Alerts</strong>
                                    <i class="fa fa-angle-right"></i>
                                </a>
                            </div>
                        </li>
                    </ul>
                </li>


                <li>
                    <a href="index.php?page=logout">
                        <i class="fa fa-power-off"></i> Log out
                    </a>
                </li>
            </ul>

        </nav>            </div>
            <div class="wrapper wrapper-content">
                <div class="row">
                    <div class="col-lg-3">
                        <div class="ibox float-e-margins">
                            <div class="ibox-title">
                                <a href=""> <label class="label label-primary pull-right"> More Details</label></a>
                                <h5><label class="label label-success">Income</label></h5>
                            </div>
                            <div class="ibox-content">
                                <h1 class="no-margins">
                                    2,151,818 INR                                </h1>
                                <div class="stat-percent font-bold text-success">98% <i class="fa fa-bolt"></i></div>
                                <small>Total Income</small>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="ibox float-e-margins">
                            <div class="ibox-title">
                                <a href=""> <label class="label label-primary pull-right"> More Details</label></a>
                                <h5><label class="label label-success">Expenditure</label></h5>
                            </div>
                            <div class="ibox-content">
                                <h1 class="no-margins">
                                    1,000,000 INR                                </h1>
                                <div class="stat-percent font-bold text-info">20% <i class="fa fa-level-up"></i></div>
                                <small>Total Expenditure</small>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="ibox float-e-margins">
                            <div class="ibox-title">
                                <a href=""> <label class="label label-primary pull-right"> More Details</label></a>
                                <h5><label class="label label-success">O Level Students</label></h5>
                            </div>
                            <div class="ibox-content">
                                <h1 class="no-margins">
                                    6                                </h1>
                                <div class="stat-percent font-bold text-navy">44% <i class="fa fa-level-up"></i></div>
                                <small>Number of Students</small>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3">
                        <div class="ibox float-e-margins">
                            <div class="ibox-title">
                                <a href=""> <label class="label label-primary pull-right"> More Details</label></a>
                                <h5><label class="label label-success">A Level Students</label></h5>
                            </div>
                            <div class="ibox-content">
                                <h1 class="no-margins">
                                    4                                </h1>
                                <div class="stat-percent font-bold text-danger">38% <i class="fa fa-level-down"></i></div>
                                <small>Number of Students</small>
                            </div>
                        </div>
                    </div>
                </div> 
                <!-- Display only four announcements here -->
                <div class="row">
                    <div class="col-lg-12">
                        <div class="ibox float-e-margins">
                            <div class="ibox-title">
                                <a href=""> <label class="label label-primary pull-right"> More Details</label></a>
                                <h5><label class="label label-success">Announcements</label></h5>
                            </div>
                            <div class="ibox-content">
                                                                      <label class="label label-primary">11 Nov 2019</label>
                                      <p>Results will be out at Jan-1-2020</p>
                                      <hr/>
                                                              </div>
                        </div>
                    </div>
                </div>
                
                <div class="row">
                    <div class="col-lg-4">
                        <div class="ibox float-e-margins">
                            <div class="ibox-title">
                                <h5><label class="label label-success">Class Teachers</label></h5>
                                <div class="ibox-tools">
                                    <a href="#"><label class="label label-primary">More Details</label></a>
                                </div>
                            </div>
                            <div class="ibox-content">
                                <table class="table table-hover no-margins">
                                    <thead>
                                        <tr>
                                            <th>#</th>
                                            <th>Class</th>
                                            <th>Teacher Name</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                                                            </tbody>
                                </table>
                            </div>
                        </div>
                    </div>

                    <div class="col-lg-8">

                        <div class="row">
                            <div class="col-lg-6">
                                <div class="ibox float-e-margins">
                                    <div class="ibox-title">
                                        <h5><label class="label label-success">O Level Subjects</label></h5>
                                        <div class="ibox-tools">
                                            <a href="index.php?page=registered_subjects&level_type=O&token=ecacd121f0885f3cbe934123726fd705"><label class="label label-primary">More Details</label></a>
                                        </div>
                                    </div>
                                    <div class="ibox-content">
                                        <table class="table table-hover no-margins">
                                            <thead>
                                                <tr>
                                                    <th>#</th>
                                                    <th>Subject Code</th>
                                                    <th>Subject Name</th>
                                                </tr>
                                            </thead>
                                            <tbody>
                                                                                                    <tr>
                                                        <td>1</td>
                                                        <td>112 </td>
                                                        <td>ENGLISH </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>2</td>
                                                        <td>113 </td>
                                                        <td>LITERATURE </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>3</td>
                                                        <td>203 </td>
                                                        <td>CRE </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>4</td>
                                                        <td>204 </td>
                                                        <td>HISTORY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>5</td>
                                                        <td>205 </td>
                                                        <td>MATHEMATICS </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>6</td>
                                                        <td>207 </td>
                                                        <td>AGRICULTURE </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>7</td>
                                                        <td>301 </td>
                                                        <td>PHYSICS </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>8</td>
                                                        <td>302 </td>
                                                        <td>CHEMISTRY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>9</td>
                                                        <td>303 </td>
                                                        <td>BIOLOGY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>10</td>
                                                        <td>305 </td>
                                                        <td>FINE ART </td>
                                                    </tr>
                                                                                                </tbody>
                                        </table>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-6">
                                <div class="ibox float-e-margins">
                                    <div class="ibox-title">
                                        <h5><label class="label label-success">A Level Subjects</label></h5>
                                        <div class="ibox-tools">
                                            <a href="index.php?page=registered_subjects&level_type=A&token=ecacd121f0885f3cbe934123726fd705"><label class="label label-primary">More Details</label></a>
                                        </div>
                                    </div>
                                    <div class="ibox-content">
                                        <table class="table table-hover no-margins">
                                            <thead>
                                                <tr>
                                                    <th>#</th>
                                                    <th>Subject Code</th>
                                                    <th>Subject Name</th>
                                                </tr>
                                            </thead>
                                            <tbody>
                                                                                                    <tr>
                                                        <td>1</td>
                                                        <td>100 </td>
                                                        <td>PHYSICS </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>2</td>
                                                        <td>101 </td>
                                                        <td>PHYSICS  </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>3</td>
                                                        <td>102 </td>
                                                        <td>PHYSICS  </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>4</td>
                                                        <td>200 </td>
                                                        <td>CHEMISTRY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>5</td>
                                                        <td>201 </td>
                                                        <td>CHEMISTRY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>6</td>
                                                        <td>202 </td>
                                                        <td>CHEMISTRY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>7</td>
                                                        <td>301 </td>
                                                        <td>BIOLOGY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>8</td>
                                                        <td>302 </td>
                                                        <td>BIOLOGY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>9</td>
                                                        <td>303 </td>
                                                        <td>BIOLOGY </td>
                                                    </tr>
                                                                                                        <tr>
                                                        <td>10</td>
                                                        <td>G8732 </td>
                                                        <td>General Paper </td>
                                                    </tr>
                                                                                                </tbody>
                                        </table>
                                    </div>
                                </div>
                            </div>

                        </div>


                    </div>
                </div>
                        <div class="footer">
            <div class="pull-right">
                <strong><font color="black"> System Developed By: </font><font color="blue">Sdev Team.</font><font color="black">  &copy; 2013 - 2020</font> </strong>
            </div>
            <div>
                <strong><font color="black"> Scholars Den</font> </strong> 
            </div>
        </div>            </div>
            <div id="right-sidebar">
                <div class="sidebar-container">

                    <ul class="nav nav-tabs navs-3">

                        <li class="active"><a data-toggle="tab" href="#tab-1">
                                Notes
                            </a></li>
                        <li><a data-toggle="tab" href="#tab-2">
                                Projects
                            </a></li>
                        <li class=""><a data-toggle="tab" href="#tab-3">
                                <i class="fa fa-gear"></i>
                            </a></li>
                    </ul>

                    <div class="tab-content">


                        <div id="tab-1" class="tab-pane active">

                            <div class="sidebar-title">
                                <h3> <i class="fa fa-comments-o"></i> Latest Notes</h3>
                                <!--<small><i class="fa fa-tim"></i> You have 10 new message.</small>-->
                            </div>

                            <div>

                                <div class="sidebar-message">
                                    <a href="#">
                                        <div class="pull-left text-center">
                                            <img alt="image" class="img-circle message-avatar" src="img/a1.jpg">

                                            <div class="m-t-xs">
                                                <i class="fa fa-star text-warning"></i>
                                                <i class="fa fa-star text-warning"></i>
                                            </div>
                                        </div>
                                        <div class="media-body">

                                            There are many variations of passages of Lorem Ipsum available.
                                            <br>
                                            <small class="text-muted">Today 4:21 pm</small>
                                        </div>
                                    </a>
                                </div>
                            </div>

                        </div>

                        <div id="tab-2" class="tab-pane">

                            <div class="sidebar-title">
                                <h3> <i class="fa fa-cube"></i> Latest projects</h3>
                                <small><i class="fa fa-tim"></i> You have 14 projects. 10 not completed.</small>
                            </div>

                            <ul class="sidebar-list">
                                <li>
                                    <a href="#">
                                        <div class="small pull-right m-t-xs">9 hours ago</div>
                                        <h4>Business valuation</h4>
                                        It is a long established fact that a reader will be distracted.

                                        <div class="small">Completion with: 22%</div>
                                        <div class="progress progress-mini">
                                            <div style="width: 22%;" class="progress-bar progress-bar-warning"></div>
                                        </div>
                                        <div class="small text-muted m-t-xs">Project end: 4:00 pm - 12.06.2014</div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="small pull-right m-t-xs">9 hours ago</div>
                                        <h4>Contract with Company </h4>
                                        Many desktop publishing packages and web page editors.

                                        <div class="small">Completion with: 48%</div>
                                        <div class="progress progress-mini">
                                            <div style="width: 48%;" class="progress-bar"></div>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="small pull-right m-t-xs">9 hours ago</div>
                                        <h4>Meeting</h4>
                                        By the readable content of a page when looking at its layout.

                                        <div class="small">Completion with: 14%</div>
                                        <div class="progress progress-mini">
                                            <div style="width: 14%;" class="progress-bar progress-bar-info"></div>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <span class="label label-primary pull-right">NEW</span>
                                        <h4>The generated</h4>
                                        <!--<div class="small pull-right m-t-xs">9 hours ago</div>-->
                                        There are many variations of passages of Lorem Ipsum available.
                                        <div class="small">Completion with: 22%</div>
                                        <div class="small text-muted m-t-xs">Project end: 4:00 pm - 12.06.2014</div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="small pull-right m-t-xs">9 hours ago</div>
                                        <h4>Business valuation</h4>
                                        It is a long established fact that a reader will be distracted.

                                        <div class="small">Completion with: 22%</div>
                                        <div class="progress progress-mini">
                                            <div style="width: 22%;" class="progress-bar progress-bar-warning"></div>
                                        </div>
                                        <div class="small text-muted m-t-xs">Project end: 4:00 pm - 12.06.2014</div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="small pull-right m-t-xs">9 hours ago</div>
                                        <h4>Contract with Company </h4>
                                        Many desktop publishing packages and web page editors.

                                        <div class="small">Completion with: 48%</div>
                                        <div class="progress progress-mini">
                                            <div style="width: 48%;" class="progress-bar"></div>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="small pull-right m-t-xs">9 hours ago</div>
                                        <h4>Meeting</h4>
                                        By the readable content of a page when looking at its layout.

                                        <div class="small">Completion with: 14%</div>
                                        <div class="progress progress-mini">
                                            <div style="width: 14%;" class="progress-bar progress-bar-info"></div>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <span class="label label-primary pull-right">NEW</span>
                                        <h4>The generated</h4>
                                        <!--<div class="small pull-right m-t-xs">9 hours ago</div>-->
                                        There are many variations of passages of Lorem Ipsum available.
                                        <div class="small">Completion with: 22%</div>
                                        <div class="small text-muted m-t-xs">Project end: 4:00 pm - 12.06.2014</div>
                                    </a>
                                </li>

                            </ul>

                        </div>

                        <div id="tab-3" class="tab-pane">

                            <div class="sidebar-title">
                                <h3><i class="fa fa-gears"></i> Settings</h3>
                                <small><i class="fa fa-tim"></i> You have 14 projects. 10 not completed.</small>
                            </div>

                            <div class="setings-item">
                                <span>
                                    Show notifications
                                </span>
                                <div class="switch">
                                    <div class="onoffswitch">
                                        <input type="checkbox" name="collapsemenu" class="onoffswitch-checkbox" id="example">
                                        <label class="onoffswitch-label" for="example">
                                            <span class="onoffswitch-inner"></span>
                                            <span class="onoffswitch-switch"></span>
                                        </label>
                                    </div>
                                </div>
                            </div>
                            <div class="setings-item">
                                <span>
                                    Disable Chat
                                </span>
                                <div class="switch">
                                    <div class="onoffswitch">
                                        <input type="checkbox" name="collapsemenu" checked class="onoffswitch-checkbox" id="example2">
                                        <label class="onoffswitch-label" for="example2">
                                            <span class="onoffswitch-inner"></span>
                                            <span class="onoffswitch-switch"></span>
                                        </label>
                                    </div>
                                </div>
                            </div>
                            <div class="setings-item">
                                <span>
                                    Enable history
                                </span>
                                <div class="switch">
                                    <div class="onoffswitch">
                                        <input type="checkbox" name="collapsemenu" class="onoffswitch-checkbox" id="example3">
                                        <label class="onoffswitch-label" for="example3">
                                            <span class="onoffswitch-inner"></span>
                                            <span class="onoffswitch-switch"></span>
                                        </label>
                                    </div>
                                </div>
                            </div>
                            <div class="setings-item">
                                <span>
                                    Show charts
                                </span>
                                <div class="switch">
                                    <div class="onoffswitch">
                                        <input type="checkbox" name="collapsemenu" class="onoffswitch-checkbox" id="example4">
                                        <label class="onoffswitch-label" for="example4">
                                            <span class="onoffswitch-inner"></span>
                                            <span class="onoffswitch-switch"></span>
                                        </label>
                                    </div>
                                </div>
                            </div>
                            <div class="setings-item">
                                <span>
                                    Offline users
                                </span>
                                <div class="switch">
                                    <div class="onoffswitch">
                                        <input type="checkbox" checked name="collapsemenu" class="onoffswitch-checkbox" id="example5">
                                        <label class="onoffswitch-label" for="example5">
                                            <span class="onoffswitch-inner"></span>
                                            <span class="onoffswitch-switch"></span>
                                        </label>
                                    </div>
                                </div>
                            </div>
                            <div class="setings-item">
                                <span>
                                    Global search
                                </span>
                                <div class="switch">
                                    <div class="onoffswitch">
                                        <input type="checkbox" checked name="collapsemenu" class="onoffswitch-checkbox" id="example6">
                                        <label class="onoffswitch-label" for="example6">
                                            <span class="onoffswitch-inner"></span>
                                            <span class="onoffswitch-switch"></span>
                                        </label>
                                    </div>
                                </div>
                            </div>
                            <div class="setings-item">
                                <span>
                                    Update everyday
                                </span>
                                <div class="switch">
                                    <div class="onoffswitch">
                                        <input type="checkbox" name="collapsemenu" class="onoffswitch-checkbox" id="example7">
                                        <label class="onoffswitch-label" for="example7">
                                            <span class="onoffswitch-inner"></span>
                                            <span class="onoffswitch-switch"></span>
                                        </label>
                                    </div>
                                </div>
                            </div>

                            <div class="sidebar-content">
                                <h4>Settings</h4>
                                <div class="small">
                                    I belive that. Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                                    And typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.
                                    Over the years, sometimes by accident, sometimes on purpose (injected humour and the like).
                                </div>
                            </div>

                        </div>
                    </div>

                </div>



            </div>
        </div>

        <!-- Mainly scripts -->
        <script src="js/jquery-2.1.1.js"></script>
        <script src="js/bootstrap.min.js"></script>
        <script src="js/plugins/metisMenu/jquery.metisMenu.js"></script>
        <script src="js/plugins/slimscroll/jquery.slimscroll.min.js"></script>

        <!-- Flot -->
<!--        <script src="js/plugins/flot/jquery.flot.js"></script>-->
<!--        <script src="js/plugins/flot/jquery.flot.tooltip.min.js"></script>-->
<!--        <script src="js/plugins/flot/jquery.flot.spline.js"></script>-->
<!--        <script src="js/plugins/flot/jquery.flot.resize.js"></script>-->
<!--        <script src="js/plugins/flot/jquery.flot.pie.js"></script>-->
<!--        <script src="js/plugins/flot/jquery.flot.symbol.js"></script>-->
<!--        <script src="js/plugins/flot/jquery.flot.time.js"></script>-->

        <!-- Peity -->
        <script src="js/plugins/peity/jquery.peity.min.js"></script>
        <script src="js/demo/peity-demo.js"></script>

        <!-- Custom and plugin javascript -->
        <script src="js/inspinia.js"></script>
        <script src="js/plugins/pace/pace.min.js"></script>

        <!-- jQuery UI -->
        <script src="js/plugins/jquery-ui/jquery-ui.min.js"></script>

        <!-- Jvectormap -->
        <script src="js/plugins/jvectormap/jquery-jvectormap-1.2.2.min.js"></script>
        <script src="js/plugins/jvectormap/jquery-jvectormap-world-mill-en.js"></script>

        <!-- EayPIE -->
        <script src="js/plugins/easypiechart/jquery.easypiechart.js"></script>

        <!-- Sparkline -->
        <script src="js/plugins/sparkline/jquery.sparkline.min.js"></script>

        <!-- Sparkline demo data  -->
        <script src="js/demo/sparkline-demo.js"></script>

        <script>
            $(document).ready(function () {
                $('.chart').easyPieChart({
                    barColor: '#f8ac59',
                    //                scaleColor: false,
                    scaleLength: 5,
                    lineWidth: 4,
                    size: 80
                });

                $('.chart2').easyPieChart({
                    barColor: '#1c84c6',
                    //                scaleColor: false,
                    scaleLength: 5,
                    lineWidth: 4,
                    size: 80
                });

                var data2 = [
                    [gd(2012, 1, 1), 7], [gd(2012, 1, 2), 6], [gd(2012, 1, 3), 4], [gd(2012, 1, 4), 8],
                    [gd(2012, 1, 5), 9], [gd(2012, 1, 6), 7], [gd(2012, 1, 7), 5], [gd(2012, 1, 8), 4],
                    [gd(2012, 1, 9), 7], [gd(2012, 1, 10), 8], [gd(2012, 1, 11), 9], [gd(2012, 1, 12), 6],
                    [gd(2012, 1, 13), 4], [gd(2012, 1, 14), 5], [gd(2012, 1, 15), 11], [gd(2012, 1, 16), 8],
                    [gd(2012, 1, 17), 8], [gd(2012, 1, 18), 11], [gd(2012, 1, 19), 11], [gd(2012, 1, 20), 6],
                    [gd(2012, 1, 21), 6], [gd(2012, 1, 22), 8], [gd(2012, 1, 23), 11], [gd(2012, 1, 24), 13],
                    [gd(2012, 1, 25), 7], [gd(2012, 1, 26), 9], [gd(2012, 1, 27), 9], [gd(2012, 1, 28), 8],
                    [gd(2012, 1, 29), 5], [gd(2012, 1, 30), 8], [gd(2012, 1, 31), 25]
                ];

                var data3 = [
                    [gd(2012, 1, 1), 800], [gd(2012, 1, 2), 500], [gd(2012, 1, 3), 600], [gd(2012, 1, 4), 700],
                    [gd(2012, 1, 5), 500], [gd(2012, 1, 6), 456], [gd(2012, 1, 7), 800], [gd(2012, 1, 8), 589],
                    [gd(2012, 1, 9), 467], [gd(2012, 1, 10), 876], [gd(2012, 1, 11), 689], [gd(2012, 1, 12), 700],
                    [gd(2012, 1, 13), 500], [gd(2012, 1, 14), 600], [gd(2012, 1, 15), 700], [gd(2012, 1, 16), 786],
                    [gd(2012, 1, 17), 345], [gd(2012, 1, 18), 888], [gd(2012, 1, 19), 888], [gd(2012, 1, 20), 888],
                    [gd(2012, 1, 21), 987], [gd(2012, 1, 22), 444], [gd(2012, 1, 23), 999], [gd(2012, 1, 24), 567],
                    [gd(2012, 1, 25), 786], [gd(2012, 1, 26), 666], [gd(2012, 1, 27), 888], [gd(2012, 1, 28), 900],
                    [gd(2012, 1, 29), 178], [gd(2012, 1, 30), 555], [gd(2012, 1, 31), 993]
                ];


                var dataset = [
                    {
                        label: "Number of orders",
                        data: data3,
                        color: "#1ab394",
                        bars: {
                            show: true,
                            align: "center",
                            barWidth: 24 * 60 * 60 * 600,
                            lineWidth: 0
                        }

                    }, {
                        label: "Payments",
                        data: data2,
                        yaxis: 2,
                        color: "#464f88",
                        lines: {
                            lineWidth: 1,
                            show: true,
                            fill: true,
                            fillColor: {
                                colors: [{
                                        opacity: 0.2
                                    }, {
                                        opacity: 0.2
                                    }]
                            }
                        },
                        splines: {
                            show: false,
                            tension: 0.6,
                            lineWidth: 1,
                            fill: 0.1
                        },
                    }
                ];


                var options = {
                    xaxis: {
                        mode: "time",
                        tickSize: [3, "day"],
                        tickLength: 0,
                        axisLabel: "Date",
                        axisLabelUseCanvas: true,
                        axisLabelFontSizePixels: 12,
                        axisLabelFontFamily: 'Arial',
                        axisLabelPadding: 10,
                        color: "#d5d5d5"
                    },
                    yaxes: [{
                            position: "left",
                            max: 1070,
                            color: "#d5d5d5",
                            axisLabelUseCanvas: true,
                            axisLabelFontSizePixels: 12,
                            axisLabelFontFamily: 'Arial',
                            axisLabelPadding: 3
                        }, {
                            position: "right",
                            clolor: "#d5d5d5",
                            axisLabelUseCanvas: true,
                            axisLabelFontSizePixels: 12,
                            axisLabelFontFamily: ' Arial',
                            axisLabelPadding: 67
                        }
                    ],
                    legend: {
                        noColumns: 1,
                        labelBoxBorderColor: "#000000",
                        position: "nw"
                    },
                    grid: {
                        hoverable: false,
                        borderWidth: 0
                    }
                };

                function gd(year, month, day) {
                    return new Date(year, month - 1, day).getTime();
                }

                var previousPoint = null, previousLabel = null;

                $.plot($("#flot-dashboard-chart"), dataset, options);

                var mapData = {
                    "US": 298,
                    "SA": 200,
                    "DE": 220,
                    "FR": 540,
                    "CN": 120,
                    "AU": 760,
                    "BR": 550,
                    "IN": 200,
                    "GB": 120,
                };

                $('#world-map').vectorMap({
                    map: 'world_mill_en',
                    backgroundColor: "transparent",
                    regionStyle: {
                        initial: {
                            fill: '#e4e4e4',
                            "fill-opacity": 0.9,
                            stroke: 'none',
                            "stroke-width": 0,
                            "stroke-opacity": 0
                        }
                    },
                    series: {
                        regions: [{
                                values: mapData,
                                scale: ["#1ab394", "#22d6b1"],
                                normalizeFunction: 'polynomial'
                            }]
                    },
                });
            });
        </script>
    </body>

    <!-- Mirrored from webapplayers.com/inspinia_admin-v2.1/dashboard_2.html by HTTrack Website Copier/3.x [XR&CO'2013], Sun, 31 May 2015 10:00:37 GMT -->
</html>
