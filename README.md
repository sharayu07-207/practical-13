# practical-13
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Mini Project</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
    
        body {
            background-color: #f4f7f6;
        }
        .hero-bg {
            background-color: #ffffff;
            border-bottom: 2px solid #dee2e6;
        }
        .footer-custom {
            background-color: #212529;
            color: white;
            padding: 20px 0;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-primary shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">MyWebsite</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navContent">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navContent">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">
                            Categories
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Frontend</a></li>
                            <li><a class="dropdown-item" href="#">Backend</a></li>
                            <li><hr class="dropdown-divider"></li>
                            <li><a class="dropdown-item" href="#">Full Stack</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container mt-4">
        <nav aria-label="breadcrumb">
            <ol class="breadcrumb bg-white p-3 rounded shadow-sm">
                <li class="breadcrumb-item"><a href="#">Dashboard</a></li>
                <li class="breadcrumb-item"><a href="#">User Portal</a></li>
                <li class="breadcrumb-item active" aria-current="page">Contact Form</li>
            </ol>
        </nav>
    </div>

    <div class="container my-5">
        <div class="row align-items-center g-5">
            <div class="col-lg-6">
                <h1 class="display-5 fw-bold text-dark mb-3">Responsive Component Showcase</h1>
                <p class="lead text-secondary">
                    This mini-site demonstrates the use of Bootstrap's grid system, interactive modals, and form validation. 
                    It is fully responsive and adjusts perfectly to mobile, tablet, and desktop screens.
                </p>
                <button class="btn btn-outline-primary btn-lg" data-bs-toggle="modal" data-bs-target="#detailsModal">
                    View Project Details
                </button>
            </div>
            <div class="col-lg-6">
                <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=500&q=80" 
                     class="img-fluid rounded-3 shadow" alt="Project Image">
            </div>
        </div>
    </div>

    <div class="container mb-5">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card shadow border-0">
                    <div class="card-header bg-dark text-white py-3">
                        <h5 class="mb-0">Registration Form</h5>
                    </div>
                    <div class="card-body p-4">
                        <form>
                            <div class="row mb-3">
                                <div class="col-md-6">
                                    <label class="form-label">First Name</label>
                                    <input type="text" class="form-control" placeholder="Enter first name">
                                </div>
                                <div class="col-md-6">
                                    <label class="form-label">Last Name</label>
                                    <input type="text" class="form-control" placeholder="Enter last name">
                                </div>
                            </div>
                            <div class="mb-3">
                                <label class="form-label">Email Address</label>
                                <input type="email" class="form-control" placeholder="email@example.com">
                            </div>
                            <div class="mb-3">
                                <label class="form-label">Department</label>
                                <select class="form-select">
                                    <option selected disabled>Choose your department...</option>
                                    <option value="1">Engineering</option>
                                    <option value="2">Human Resources</option>
                                    <option value="3">Marketing</option>
                                </select>
                            </div>
                            <div class="mb-4">
                                <label class="form-label">Additional Comments</label>
                                <textarea class="form-control" rows="3"></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary px-5">Submit Application</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="modal fade" id="detailsModal" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Project Documentation</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <p>This project was built using:</p>
                    <ul>
                        <li><strong>Bootstrap 5.3:</strong> For layout and UI.</li>
                        <li><strong>HTML5/CSS3:</strong> For structure and style.</li>
                        <li><strong>Responsive Design:</strong> Mobile-first approach.</li>
                    </ul>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary">Okay</button>
                </div>
            </div>
        </div>
    </div>

    <footer class="footer-custom text-center">
        <div class="container">
            <small>&copy; 2026 Developer Portfolio. All Rights Reserved.</small>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
