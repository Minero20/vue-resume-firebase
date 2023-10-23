<template>
    <div style="font-family: Sofia, sans-serif; background-color: #000000;">
        <link rel="stylesheet" href="index_style.css" />
        <title> My Resume </title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <div>
            <div class="row">
                <div class="col-3 text-center align-self-center rainbow-text">
                    ██╗░░░██╗███████╗░██████╗
                    ╚██╗░██╔╝██╔════╝██╔════╝
                    ░╚████╔╝░█████╗░░╚█████╗░
                    ░░╚██╔╝░░██╔══╝░░░╚═══██╗
                    ░░░██║░░░███████╗██████╔╝
                    ░░░╚═╝░░░╚══════╝╚═════╝░
                    ██╗░░░██╗███████╗░██████╗
                    ╚██╗░██╔╝██╔════╝██╔════╝
                    ░╚████╔╝░█████╗░░╚█████╗░
                    ░░╚██╔╝░░██╔══╝░░░╚═══██╗
                    ░░░██║░░░███████╗██████╔╝
                    ░░░╚═╝░░░╚══════╝╚═════╝░
                    ██╗░░░██╗███████╗░██████╗
                    ╚██╗░██╔╝██╔════╝██╔════╝
                    ░╚████╔╝░█████╗░░╚█████╗░
                    ░░╚██╔╝░░██╔══╝░░░╚═══██╗
                    ░░░██║░░░███████╗██████╔╝
                    ░░░╚═╝░░░╚══════╝╚═════╝░
                    ██╗░░░██╗███████╗░██████╗
                    ╚██╗░██╔╝██╔════╝██╔════╝
                    ░╚████╔╝░█████╗░░╚█████╗░
                    ░░╚██╔╝░░██╔══╝░░░╚═══██╗
                    ░░░██║░░░███████╗██████╔╝
                    ░░░╚═╝░░░╚══════╝╚═════╝░
                </div>
                <div class="col-6 align-items-center">
                    <div class="shadow p-4 bg-white border border-light" style="height: 629px;">    
                        <h1 class="rounded-pill title"> My Portfolio </h1> 
                        <div class="row" style="padding: 25px;">
                            <div class="col" style="margin-top: 0px;">
                                <img src="../assets/S__35749896.jpg" alt="myPhoto" class="img-thumbnail" width="350" height="300">
                            </div>
                            <div class="col">
                                <div class="container mt-3">         
                                    <table class="table table-hover">
                                        <thead>
                                            <tr>
                                                <h2>Information</h2> 
                                            </tr>
                                        </thead>
                                        <tbody>
                                            <tr>
                                                <td>Name : {{ name }} </td>
                                            </tr>
                                            <tr>
                                                <td>Nickname : {{ nickname }} </td>
                                            </tr>
                                            <tr>
                                                <td>Age : {{ age }} </td>
                                            </tr>
                                            <tr>
                                                <td>Birthday : {{ dob }} </td>
                                            </tr>
                                            <tr>
                                                <td>Sex : {{ gender }} </td>
                                            </tr>
                                            <tr>
                                                <td>Religion : {{ religion }} </td>
                                            </tr>
                                            <tr>
                                                <td>Nationality : {{ nationality }} </td>
                                            </tr>
                                            <tr>
                                                <td>Blood group : {{ bloodgroup }} </td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </div>
                                <button type="button" class="btn btn-outline-secondary" style="margin-left: 2px; margin-right: 50 px; margin-top: 10px;">Read More</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-3 text-center align-self-center rainbow-text">
                    ██╗░░░██╗███████╗░██████╗
                    ╚██╗░██╔╝██╔════╝██╔════╝
                    ░╚████╔╝░█████╗░░╚█████╗░
                    ░░╚██╔╝░░██╔══╝░░░╚═══██╗
                    ░░░██║░░░███████╗██████╔╝
                    ░░░╚═╝░░░╚══════╝╚═════╝░
                    ██╗░░░██╗███████╗░██████╗
                    ╚██╗░██╔╝██╔════╝██╔════╝
                    ░╚████╔╝░█████╗░░╚█████╗░
                    ░░╚██╔╝░░██╔══╝░░░╚═══██╗
                    ░░░██║░░░███████╗██████╔╝
                    ░░░╚═╝░░░╚══════╝╚═════╝░
                    ██╗░░░██╗███████╗░██████╗
                    ╚██╗░██╔╝██╔════╝██╔════╝
                    ░╚████╔╝░█████╗░░╚█████╗░
                    ░░╚██╔╝░░██╔══╝░░░╚═══██╗
                    ░░░██║░░░███████╗██████╔╝
                    ░░░╚═╝░░░╚══════╝╚═════╝░
                    ██╗░░░██╗███████╗░██████╗
                    ╚██╗░██╔╝██╔════╝██╔════╝
                    ░╚████╔╝░█████╗░░╚█████╗░
                    ░░╚██╔╝░░██╔══╝░░░╚═══██╗
                    ░░░██║░░░███████╗██████╔╝
                    ░░░╚═╝░░░╚══════╝╚═════╝░
                </div>
            </div>
        </div>
        <footer class="text-center p-3"> made by {{ name }} </footer>
    </div>
</template>

<script>
export default {
    name: 'MyResume',
    data() {
        return {
            name: 'Pisit Namsiri',
            nickname: 'Pound',
            age: '20',
            dob: '2 january 2003',
            gender: 'male',
            religion: 'Buddhism',
            nationality: 'Thai',
            bloodgroup: 'B'
        };
    },
};
</script>

<style scoped>
.rainbow-text {
    font-size: 17px;
    font-weight: bold;
    background: linear-gradient(45deg, red, orange, yellow, green, blue, indigo, violet);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    animation: rainbow 3s linear infinite;
    background-size: 200% 200%;
    }

@keyframes rainbow {
    0% {
        background-position: 0 0;
    }
    100% {
        background-position: 100% 250%;
    }
}

.title
{
    background-color:#333;
    color: #ffffff; 
    margin-bottom: 15px;
    padding: 15px;
    text-align: center;
    display: flex;
    flex-direction: row;
}
.title:before, .title:after 
{
    content: "";
    flex: 1 1;
    border-bottom: 2px solid rgb(255, 255, 255);
    margin: auto;
}
.column
{
    column-count: 2;
    column-gap: 5px;
    column-rule: 1px solid lightblue;
    width: 700px;  
    background: rgb(255, 255, 255); 
}
.text
{
    width: 0px; 
    right: 0; 
    top: 0; 
    bottom: 0; 
    background: rgb(255, 255, 255); 
    color:rgb(0, 0, 0)
}
.box
{
    background-color: #ffffff;
    width: 50%;
    margin: auto;
    padding: 20px;
}
footer
{
    background-color: #333;
    color: #fffefe;
    padding: 10px;
    text-align: right;
}
.columns
{
    float: left;
    width: 50%;
    margin: auto;
    padding: 10px;
    height: 700px; 
}
.row:after 
{
    content: "";
    display: table;
    clear: both;
}
/* ---- */
/* .container {
    max-width: 960px;
}

header {
    h1 {
    font-size: 2rem;
    font-weight: bold;
    }

    a {
    color: blue;
    text-decoration: none;
    }
}

section {
    h2 {
    font-size: 1.5rem;
    font-weight: bold;
    }

    ul {
    list-style-type: none;
    padding-left: 1rem;
    }

    li {
    margin-bottom: 0.5rem;
    }
} */
</style>
