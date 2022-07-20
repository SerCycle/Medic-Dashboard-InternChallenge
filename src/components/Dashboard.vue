<template>
    <div class="container-fluid shadow sticky-top" style="background-color: white;">
        <div class="row justify-content-between">
            <div class="p-2 col-auto col-md-3 col-xl-2 d-flex justify-content-around align-items-center">
                <p class="d-flex align-items-center m-0">🎯 Practice makes perfect</p>
                <a href="" class="ps-5 d-flex align-items-center m-0"><img src="../assets/menu.png" alt="" width="20px" ></a>
            </div>
            <div class="p-2  col-auto col-md-3 col-xl-3 me-1">
                <div class="row justify-content-between">
                    <a href="" class="col-auto d-flex align-items-center m-0"><img src="../assets/bell.png" alt="" width="20px" ></a>
                    <a href="" class="col-auto d-flex align-items-center m-0"><img src="../assets/gear-option.png" alt="" width="20px" ></a>
                    <div class="col dropdown">
                        <a href="#" class="d-flex nav-link dropdown-toggle align-items-center justify-content-between" data-bs-toggle="dropdown">
                            <div class="row d-flex align-items-center">
                                <div class="p-2 text-center text-white" style="flex-direction: column; gap: 10px; width: 40px; height: 40px; background: #358EF6; border-radius: 100px;">SR</div>
                                <div class="col m-0">
                                    <p class="m-0"><b>Jamilah Nur Jamalah</b></p>
                                    <p class="m-0">Super Admin</p>
                                </div>
                            </div>
                        </a>
                        <div class="dropdown-menu dropdown-menu-end">
                            <a href="#" class="dropdown-item">Profile</a>
                            <a href="#" class="dropdown-item">Settings</a>
                            <div class="dropdown-divider"></div>
                            <a href="#" class="dropdown-item">Logout</a>
                        </div>
                    </div>
                    
                </div>
                
            </div>
        </div>
    </div>

    <div class="container-fluid justify-content-between row">
        <div class="col-auto" style="width: 13rem;  background: #358EF6;">
            <div class="row">
                <div class="col-auto col-md-3 col-xl-2 px-sm-2 " style="">
                    <div class="d-flex flex-column align-items-center align-items-sm-start px-3 pt-2 text-white min-vh-100">
                        <ul class="nav nav-pills flex-column mb-sm-auto mb-0 align-items-center align-items-sm-start" id="menu" style="width: 11rem; position: fixed;">
                            <li class="nav-item">
                                <a href="#" class="nav-link align-middle px-0">
                                    <img src="../assets/progress.png" alt="" width="20px"><span class="ms-1 text-white">Dashboard</span>
                                </a>
                            </li>
                            <li>
                                <a href="#submenu1" data-bs-toggle="collapse" class="nav-link px-0 align-middle">
                                    <img src="../assets/doctor.png" alt="" width="20px"><span class="ms-1 text-white">Doctor Management</span> </a>
                                <ul class="collapse show nav flex-column ms-2 rounded ps-3 pe-3" id="submenu1" data-bs-parent="#menu" style="background: #2563AC;">
                                    <li class="w-100">
                                        <a href="#" class="nav-link px-0"> <span class="d-sm-inline text-white">Doctor Data</span></a>
                                    </li>
                                    <li>
                                        <a href="#" class="nav-link px-0"> <span class="d-sm-inline text-white">Doctor Transaction</span></a>
                                    </li>
                                </ul>
                            </li>
                            <li>
                                <a href="#" class="nav-link px-0 align-middle">
                                    <img src="../assets/calender.png" alt="" width="20px"><span class="ms-1 text-white">Appointment</span></a>
                            </li>
                        </ul>
                    </div>
                </div> 
            </div>
        </div>
        
        <div class="col-auto py-3" style="font-family: 'Poppins', sans-serif;">
            Dashboard/
            <h1><b>Dashboard</b></h1>
            <div class="container">
                <!-- section 1 -->
                <div class="row justify-content-between">
                    <!-- download -->
                    <div class="col-auto m-1 rounded border" style="">
                        <div class="row align-items-center">
                            <div class="col-auto" style="margin: 0;">
                                <img class="col-auto" src="../assets/IconDownloadDashboard.png" alt="" height="30px">
                            </div>
                            <div class="col-auto">
                                <p class="m-0">User Download</p>
                                <div class="row align-items-center">
                                    <h1 class="col-auto mt-1 mb-1"><b>5.12M</b></h1>
                                    <div class="col-auto">
                                        <div class="rounded-pill p-1" style="background-color: #EBF4FE; color: #57A1F8; font-size: 10px;">
                                            +200k
                                        </div>
                                    </div>
                                </div>
                                <p class="m-0 text-secondary" style="font-size: ;">per Today</p>
                            </div>
                        </div>
                    </div>
                    <!-- Active Doctor -->
                    <div class="col-auto m-1 rounded border" style="">
                        <div class="row align-items-center">
                            <div class="col-auto" style="margin: 0;">
                                <img class="col-auto" src="../assets/IconPeopleDashboard.png" alt="" height="30px">
                            </div>
                            <div class="col-auto">
                                <p class="m-0">Active Doctor</p>
                                <div class="row align-items-center">
                                    <h1 class="col-auto mt-1 mb-1"><b>1240</b></h1>
                                    <div class="col-auto">
                                        <!-- <div class="rounded-pill p-1" style="background-color: #EBF4FE; color: #57A1F8; font-size: 10px;">
                                            +24k
                                        </div> -->
                                    </div>
                                </div>
                                <p class="m-0 text-secondary" style="font-size: ;">from the Total of 10K</p>
                            </div>
                        </div>
                    </div>
                    <!-- Transaction -->
                    <div class="col-auto m-1 rounded border" style="">
                        <div class="row align-items-center">
                            <div class="col-auto" style="margin: 0;">
                                <img class="col-auto" src="../assets/IconDolarDashboard.png" alt="" height="30px">
                            </div>
                            <div class="col-auto">
                                <p class="m-0">Today Transaction</p>
                                <div class="row align-items-center">
                                    <h1 class="col-auto mt-1 mb-1"><b>125K</b></h1>
                                    <div class="col-auto">
                                        <div class="rounded-pill p-1" style="background-color: #EBF4FE; color: #57A1F8; font-size: 10px;">
                                            +24k
                                        </div>
                                    </div>
                                </div>
                                <p class="m-0 text-secondary" style="font-size: ;">update 13:33 WIB</p>
                            </div>
                        </div>
                    </div>
                    <!-- Happines -->
                    <div class="col-auto m-1 rounded border" style="">
                        <div class="row align-items-center">
                            <div class="col-auto" style="margin: 0;">
                                <img class="col-auto" src="../assets/IconStarDashboard.png" alt="" height="30px">
                            </div>
                            <div class="col-auto">
                                <p class="m-0">Customer Happiness</p>
                                <div class="row align-items-center">
                                    <h1 class="col-auto mt-1 mb-1"><b>4.5</b></h1>
                                    <div class="col-auto">
                                        <div class="rounded-pill p-1" style="background-color: #EBF4FE; color: #57A1F8; font-size: 10px;">
                                            +23
                                        </div>
                                    </div>
                                </div>
                                <p class="m-0 text-secondary" style="font-size: ;">from 1.2M Number of Reviews</p>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- section 2 -->
                <div class="row">
                    <div class="rounded border m-1">
                        <h5 class="p-2"><b>Transaction</b></h5>
                        <div class="row d-flex justify-content-end align-items-center">
                            <div class="col-auto text-secondary" style="font-size: 12px;">From:</div>
                            <div class="col-auto">
                                <input class="form-control bg-secondary bg-opacity-25" type="date" value="2022-02-01" style="font-size: 12px;">
                            </div>
                            <div class="col-auto text-secondary" style="font-size: 12px;">to:</div>
                            <div class="col-auto">
                                <input class="form-control bg-secondary bg-opacity-25" type="date" value="2022-02-10" style="font-size: 12px;">
                            </div>
                        </div>
                        <div class="d-flex justify-content-around">
                            <div class="chart-container" style="height:50vh; width:70vw">
                                <canvas id="myChart"  style="height:50vh; width:70vw"></canvas>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- section 3 -->
                <div id="app" class="row justify-content-between">
                    <div class="rounded border m-1">
                        <h5 class="p-2"><b>Table User</b></h5>
                        <div>
                            <table class="table" style="border-radius: 10px;">
                                <thead class="text-white" style="background-color: #358EF6;">
                                    <tr>
                                        <th scope="col">Username</th>
                                        <th scope="col">Favourite Color</th>
                                        <th scope="col">Hobby</th>
                                    </tr>
                                </thead>
                                <tbody >
                                    <tr v-for="people in peoples">
                                        <td>{{ people.name }}</td>
                                        <td>
                                            <div class="rounded border" style="width: 60px; height: 20px; " :style="{ 'background-color': people.colour}"></div>
                                        </td>
                                        <td>{{people.hobby}}</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    import Chart from 'chart.js/auto';

    export default{
        name: "Dashboard",
        data(){
            return{
                peoples: [
                    {id: 0, name: 'WonderingWonder', colour: '#F5A9A9', hobby: 'Makan'},
                    {id: 1, name: 'KelinciHutan', colour: '#F7E097', hobby: 'Minum'},
                    {id: 2, name: 'BenaluMalu', colour: '#205796', hobby: 'Berenang, Berlari'},
                    {id: 4, name: 'KijangTalun', colour: '#2ECC71', hobby: 'Menyanyi'}
                ],
            }
        },
        mounted() {
            console.log('Component mounted.')

            const ctx = document.getElementById('myChart');
            const myChart = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: ['1 Feb 2022',
                            '2 Feb 2022',
                            '3 Feb 2022',
                            '4 Feb 2022',
                            '5 Feb 2022',
                            '6 Feb 2022',
                            '7 Feb 2022',
                            '8 Feb 2022',
                            '9 Feb 2022',
                            '10 Feb 2022',],
                    datasets: [{
                        label: 'Total Transaction',
                        data: [12, 19, 3, 5, 2, 3, 13, 2, 7, 8,],
                        backgroundColor: ['rgba(54, 162, 235, 1)',]
                    }]
                },
                options: {
                    label:{
                        display: false
                    },
                    scales: {
                        y: {
                            display: false
                        },
                        x: {
                            grid:{
                                display: false
                            }
                        }
                    },
                }
            });
        },
    };
</script>