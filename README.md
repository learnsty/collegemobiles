# CollegeMobile2

Built on top of the Vyke Framework v1.0.0-beta for Mobicent Nigeria Ltd.

# API Documentation

This short api documentation will highlight the components that make up the Vyke framework

## Components
 
Components are the most important tools for build web applications with the Vyke Framework. 

### Request

>This is the component controls everything about a standard HTTP request

- **Request::ip();** [gets the ip addresss of the client]
- **Request::isAjax();** [checks whether the request is an ajax request]
- **Request::input()->getFields();** [gets all parameters from any request: PUT, POST, GET, DELETE, JSONP]
- **Request::input()->getFiles();** [gets all files from a POST request]
- **Request::upload({upload_folder_name}, {errors_array});** []
- **Request::method();** [gets the request method: PUT, POST, GET, DELETE, JSONP]
- **Request::rawHeader({header_key});** []
- **Request::getCookie({cookie_key});** []

### Response

>This is the component controls everything about a standard HTTP response

- **Response::setCookie({cookie_key}, {cookie_value});** []
- **Response::header({header_key}, {header_value});** []
- **Response::file({file_name});** []
- **Response::download({file_name});** []
- **Response::json({json_text}, {status_code});** []
- **Response::text({plain_text});** []

### Session

>This is the component controls everything about a server sessions

- **Session::has({session_key});** []
- **Session::forget({session_key});** []
- **Session::get({session_key});** []