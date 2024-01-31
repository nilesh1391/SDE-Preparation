# SDE-Preparation

import React, { useContext } from 'react';
import AuthContext from '../context/AuthContext';
import './Topbar.css';

const Topbar = ({username}) => {
  const { user, logoutUser } = useContext(AuthContext);

  return (
    <nav className="navbar navbar-expand-lg navbar-light bg-light">
            <div className="container-fluid">
                <a className="navbar-brand" href="#">Ingenious Brain</a>
                <div className="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul className="navbar-nav me-auto mb-2 mb-lg-0">
                        <li className="nav-item">
                            <a className="nav-link" href="#">Home</a>
                        </li>
                        <li className="nav-item">
                            <a className="nav-link" href="#">Dashboard</a>
                        </li>
                    </ul>
                    <form className="d-flex">
                        <button className="btn btn-outline-success" type="submit">{username}</button>
                    </form>
                </div>
            </div>
        </nav>
    );
};

export default Topbar;
