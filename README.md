#MOVIEリストを作ります！

yarn install global create-react-app

create-react-app project name

yarn start

컴포넌트 만드는것 (ex: Header.js and Header.css)

import React, { Component } from 'react';
import './Header.css';

class Header extends Component{
    render(){
        return(
            <h2>header</h2>
        )
    }
}

export default Header;