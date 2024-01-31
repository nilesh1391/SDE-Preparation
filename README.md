# SDE-Preparation

.topbar {
    background-color: #e9ecef;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    display: flex;
    justify-content: space-between;
    padding: 0.5rem 1rem;
    align-items: center;
  }
  
  .topbar-item {
    margin-right: 1rem;
  }
  
  .topbar-dropdown-button {
    background: none;
    border: none;
    cursor: pointer;
  }
  
  .dropdown-menu {
    position: absolute;
    right: 1rem;
    background-color: #fff;
    padding: 0.5rem 0;
    border-radius: 0.25rem;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }



  .sidebar {
    background-color: #343a40;
    width: 250px;
    height: 100vh;
    position: fixed;
    overflow-y: auto;
    color: #fff;
    margin-top: 0;
  }
  
  .sidebar .sidebar-sticky {
    position: sticky;
    top: 0;
    height: calc(100vh - 48px); /* Adjust based on your topbar height */
    padding-top: 0.5rem;
    overflow-x: hidden;
    overflow-y: auto; /* Scrollable contents if viewport is short */
  }
  
  .sidebar-header {
    display: flex;
    align-items: center;
    padding: 0.5rem 1rem;;
    font-size: 1.2em;
  }
  
  .sidebar .sidebar-header i {
    margin-right: 10px;
  }

  .nav-item {
    padding: 5px 0;
  }
  
  .nav-link {
    color: #fff;
    padding: 0.5rem 1rem;
  }

  .nav-link:hover, .nav-link:focus {
    color: #fff;
    background-color: #495057; /* A shade darker on hover/focus */
  }
  
  .sub-menu {
    padding-left: 2rem;
  }
  
  .sub-menu .nav-item {
    padding: 5px 0;
  }
  
  .sub-menu .nav-link {
    padding-left: 30px;
  }

  .sidebar-icon {
    margin-right: 10px; /* Adjust spacing */
  }

  .fas {
    margin-right: 0.5rem;
  }



  
