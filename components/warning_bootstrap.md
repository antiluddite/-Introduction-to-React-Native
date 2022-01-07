from login component

// componentDidMount() {
//     SecureStore.getItemAsync('userinfo')
//         .then(userdata => {
//             const userinfo = JSON.parse(userdata);
//             if (userinfo) {
//                 this.setState({username: userinfo.username});
//                 this.setState({password: userinfo.password});
//                 this.setState({remember: true})
//             }
//         });
// }

// class Login extends Component {
    
//     constructor(props) {
//         super(props);

//         this.state = {
//             username: '',
//             password: '',
//             remember: false
//         };
//     }