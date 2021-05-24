<template>
    <div class="content">
        <div class="bg-content"></div>
        <div class="model"></div>
        <div class="content-data">
            <div class="search-form">
        
                <form class="fsearch">
                    <h3>FILTER FORM</h3>
                    <label>Search by location</label><br />
                    <input type="search" class="text-input" placeholder="Enter location" /><br /><br />
                    <label>Search by service</label><br />
                    <input type="search" class="text-input" placeholder="Enter service" /><br /><br />
                    <label>Search by name</label><br />
                    <input type="search" class="text-input" placeholder="Enter name" /><br /><br />

                    <button type="submit">Search</button>
                </form>
            </div>
            <div class="data-collapse">
                <div class="category">
                    <div class="restaurant">
                        <div class="infor">
                            <div class="infor-left">
                                <div class="name">Nhà hàng Hoa Tiên</div>
                                <div class="rate">Đánh giá: 4/5</div>
                                <div class="address">Địa chỉ: 1194 đường Láng</div>
                                <div class="time">Mở cửa đến 22:00</div>
                            </div>
                            <div class="infor-right">
                                <div class="imange"></div>
                            </div>
                        </div>
                        <div class="select">
                            <div class="select-left">
                                <div class="icon-pick"></div>
                                <label>Ăn tại nhà hàng</label>
                            </div>
                            <div class="select-right">
                                <div class="icon-pick"></div>
                                <label>Mua mang về</label>
                            </div>
                        </div>
                    </div>
                    <div class="restaurant">
                        <div class="infor">
                            <div class="infor-left">
                                <div class="name">Nhà hàng Suối Hoa</div>
                                <div class="rate">Đánh giá: 4.5/5</div>
                                <div class="address">Địa chỉ: 1194 đường Láng</div>
                                <div class="time">Mở cửa đến 22:00</div>
                            </div>
                            <div class="infor-right">
                                <div class="imange"></div>
                            </div>
                        </div>
                        <div class="select">
                            <div class="select-left">
                                <div class="icon-pick"></div>
                                <label>Ăn tại nhà hàng</label>
                            </div>
                            <div class="select-right">
                                <div class="icon-pick"></div>
                                <label>Mua mang về</label>
                            </div>
                        </div>
                    </div>
                    <div class="restaurant">
                        <div class="infor">
                            <div class="infor-left">
                                <div class="name">Nhà hàng Hoa Sim</div>
                                <div class="rate">Đánh giá: 4/5</div>
                                <div class="address">Địa chỉ: 1194 đường Láng</div>
                                <div class="time">Mở cửa đến 22:00</div>
                            </div>
                            <div class="infor-right">
                                <div class="imange"></div>
                            </div>
                        </div>
                        <div class="select">
                            <div class="select-left">
                                <div class="icon-pick"></div>
                                <label>Ăn tại nhà hàng</label>
                            </div>
                            <div class="select-right">
                                <div class="icon-pick"></div>
                                <label>Mua mang về</label>
                            </div>
                        </div>
                    </div>
                    <div class="restaurant">
                        <div class="infor">
                            <div class="infor-left">
                                <div class="name">Nhà hàng Hoa Mai</div>
                                <div class="rate">Đánh giá: 4/5</div>
                                <div class="address">Địa chỉ: 1194 đường Láng</div>
                                <div class="time">Mở cửa đến 22:00</div>
                            </div>
                            <div class="infor-right">
                                <div class="imange"></div>
                            </div>
                        </div>
                        <div class="select">
                            <div class="select-left">
                                <div class="icon-pick"></div>
                                <label>Ăn tại nhà hàng</label>
                            </div>
                            <div class="select-right">
                                <div class="icon-pick"></div>
                                <label>Mua mang về</label>
                            </div>
                        </div>
                    </div>
                    <div class="restaurant">
                        <div class="infor">
                            <div class="infor-left">
                                <div class="name">Nhà hàng Hoa Cúc</div>
                                <div class="rate">Đánh giá: 4/5</div>
                                <div class="address">Địa chỉ: 1194 đường Láng</div>
                                <div class="time">Mở cửa đến 22:00</div>
                            </div>
                            <div class="infor-right">
                                <div class="imange"></div>
                            </div>
                        </div>
                        <div class="select">
                            <div class="select-left">
                                <div class="icon-pick"></div>
                                <label>Ăn tại nhà hàng</label>
                            </div>
                            <div class="select-right">
                                <div class="icon-pick"></div>
                                <label>Mua mang về</label>
                            </div>
                        </div>
                    </div>
                    <div class="restaurant">
                        <div class="infor">
                            <div class="infor-left">
                                <div class="name">Nhà hàng Nhật Tân</div>
                                <div class="rate">Đánh giá: 3.5/5</div>
                                <div class="address">Địa chỉ: 1194 đường Láng</div>
                                <div class="time">Mở cửa đến 22:00</div>
                            </div>
                            <div class="infor-right">
                                <div class="imange"></div>
                            </div>
                        </div>
                        <div class="select">
                            <div class="select-left">
                                <div class="icon-pick"></div>
                                <label>Ăn tại nhà hàng</label>
                            </div>
                            <div class="select-right">
                                <div class="icon-pick"></div>
                                <label>Mua mang về</label>
                            </div>
                        </div>
                    </div>           
                </div>
                <div class="panigation">
                    <label>Đang hiển thị kết quả 1 - 10</label>
                    <button class="page-prev" id="btn-prev-page"></button>
                    <button class="page-next" id="btn-next-page"></button>  
                </div>
            </div>
            <div class="data-expand">
                <div class="background"></div>
                <div class="full-infor">
                    <div class="full-address">
                        <div class="icon-address"></div>
                        <label>Ngách 103, ngõ 1194 đường Láng</label>
                    </div>
                    <div class="status">
                        <div class="icon-status"></div>
                        <label>Mở của cả ngày</label>
                    </div>
                    <div class="phone">
                        <div class="icon-phone"></div>
                        <label>+84 941716997</label>
                    </div>
                    <div class="code-plus">
                        <div class="icon-code"></div>
                        <label>2QGP+Q9 Ninh Kiều, Cần Thơ, Việt Nam</label>
                    </div>
                    <div class="confirm">
                        <div class="icon-confirm"></div>
                        <label>Xác nhận doanh nghiệp này</label>
                    </div>
                </div>
                <div class="full-image">
                    <h3>Ảnh minh họa</h3>
                    <div class="album-img">
                        <img class="element-img" src="../../assets/display-img.jpg" />
                        <img class="element-img" src="../../assets/display-img.jpg" />
                        <img class="element-img" src="../../assets/display-img.jpg" />
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.content {
    width: 100%;
    height: calc(100vh - 60px);
    color: black;
}

    .content .bg-content {
        height: 100%;
        background-image: url('../../assets/Worldmap-blank.svg');
        background-size: contain;
        background-position: center;
        background-repeat: no-repeat;
    }
    .content .model {
        position: absolute;
        top: 60px;
        width: 100%;
        height: calc(100vh - 60px);
        background-color: white;
        opacity: 100%;
    }
    .content .content-data {
        position: absolute;
        top: 60px;
        width: 100%;
        height: calc(100vh - 60px);
        display: flex;
    }
    .content-data .search-form {
        width: 20%;
        margin-left: 5%;
        height: calc(100vh - 60px);
        position: relative;
    }
    .search-form .fsearch {
        width: 100%;
        position: absolute;
        top: 40%;
        left: 50%;
        transform: translate(-50%, -50%);
    }




















.content-data .data-collapse {
    width: 25%;
    height: calc(100vh - 60px);
}

.content-data .data-collapse .category {
    overflow: auto;
    width: 100%;
    height: calc(100% - 34px);
}

    .content-data .data-collapse .category .restaurant {
        width: calc(100% - 1px);
        height: 150px;
        border-left: 1px solid #bbbbbb;
        border-bottom: 1px solid #bbbbbb;
    }

        .content-data .data-collapse .category .restaurant .infor {
            width: 100%;
            height: 100px;
            display: flex;
        }

            .content-data .data-collapse .category .restaurant .infor .infor-left {
                width: 55%;
                height: 100%;
                margin-left: 5%;
            }

                .content-data .data-collapse .category .restaurant .infor .infor-left .name {
                    font-size: 20px;
                    margin-top: 12px;
                }

                .content-data .data-collapse .category .restaurant .infor .infor-left .rate {
                    margin-top: 6px;
                }

                .content-data .data-collapse .category .restaurant .infor .infor-left .address {
                    margin-top: 6px;
                }

                .content-data .data-collapse .category .restaurant .infor .infor-left .time {
                    margin-top: 6px;
                }

            .content-data .data-collapse .category .restaurant .infor .infor-right {
                background-image: url(../../assets/mon-an.jpeg);
                background-size: contain;
                background-position: center;
                background-repeat: no-repeat;
                margin-top: 12px;
                margin-left: 16px;
                width: 90px;
                height: 90px;
            }

        .content-data .data-collapse .category .restaurant .select {
            width: 95%;
            height: 30px;
            display: flex;
            margin-left: 5%;
            margin-top: 20px;
        }

            .content-data .data-collapse .category .restaurant .select .select-left {
                display: flex;
            }

                .content-data .data-collapse .category .restaurant .select .select-left .icon-pick {
                    background: url('../../assets/common-icon.png') no-repeat -177px -3px;
                    width: 16px;
                    height: 16px;
                }

            .content-data .data-collapse .category .restaurant .select .select-right {
                margin-left: 12px;
                display: flex;
            }

                .content-data .data-collapse .category .restaurant .select .select-right .icon-pick {
                    background: url('../../assets/common-icon.png') no-repeat -177px -3px;
                    width: 16px;
                    height: 16px;
                }

            .content-data .data-collapse .category .restaurant .select label {
                margin-left: 4px;
            }

        .content-data .data-collapse .category .restaurant:hover {
            cursor: pointer;
            background-color: #bbbbbb;
        }

        .content-data .data-collapse .category .restaurant:focus {
            background-color: #0094ff;
        }

.content-data .data-collapse .panigation {
    width: calc(100% - 2px);
    height: 32px;
    border: 1px solid #bbbbbb;
    display: flex;
}

    .content-data .data-collapse .panigation label {
        width: 55%;
        margin-top: 8px;
        margin-left: 5%;
        font-size: 12px;
        color: #000000;
    }

    .content-data .data-collapse .panigation .page-prev {
        background: url('../../assets/common-icon.png') no-repeat -702px -126px;
        width: 24px;
        height: 24px;
        border: 1px solid #0009b6;
        border: none;
        margin-top: 6px;
        cursor: pointer;
    }

    .content-data .data-collapse .panigation .page-next {
        background: url('../../assets/common-icon.png') no-repeat -752px -126px;
        width: 24px;
        height: 24px;
        border: 1px solid #0009b6;
        margin-left: 16px;
        border: none;
        margin-top: 6px;
        justify-content: flex-end;
        cursor: pointer;
    }

.content-data .data-expand {
    width: 40%;
    height: calc(100vh - 60px);
    margin-left: 5%;
}

    .content-data .data-expand .background {
        width: 100%;
        height: 30%;
        background-image: url(../../assets/mon-an.jpeg);
        background-size: contain;
        background-position: center;
        background-repeat: no-repeat;
    }

    .content-data .data-expand .full-infor {
        width: 100%;
        height: 30%;
    }

        .content-data .data-expand .full-infor .full-address {
            display: flex;
        }

        .content-data .data-expand .full-infor .icon-address {
            background: url('../../assets/common-icon.png') no-repeat -153px -2px;
            width: 13px;
            height: 16px;
            margin-left: 8px;
            margin-top: 16px;
        }

        .content-data .data-expand .full-infor label {
            margin-left: 8px;
            margin-top: 16px;
        }

        .content-data .data-expand .full-infor .status {
            display: flex;
            margin-left: 8px;
        }

        .content-data .data-expand .full-infor .icon-status {
            background: url('../../assets/common-icon.png') no-repeat -27px -202px;
            width: 16px;
            height: 16px;
            margin-top: 16px;
        }

        .content-data .data-expand .full-infor .phone {
            display: flex;
            margin-left: 8px;
        }

        .content-data .data-expand .full-infor .icon-phone {
            background: url('../../assets/common-icon.png') no-repeat -54px -3px;
            width: 12px;
            height: 15px;
            margin-top: 16px;
        }

        .content-data .data-expand .full-infor .code-plus {
            display: flex;
        }

        .content-data .data-expand .full-infor .icon-code {
            background: url('../../assets/common-icon.png') no-repeat -153px -2px;
            width: 13px;
            height: 16px;
            margin-left: 8px;
            margin-top: 16px;
        }

        .content-data .data-expand .full-infor label {
            margin-left: 8px;
            margin-top: 16px;
        }

        .content-data .data-expand .full-infor .confirm {
            display: flex;
        }

        .content-data .data-expand .full-infor .icon-confirm {
            background: url('../../assets/common-icon.png') no-repeat -153px -2px;
            width: 13px;
            height: 16px;
            margin-left: 8px;
            margin-top: 16px;
        }

        .content-data .data-expand .full-infor label {
            margin-left: 8px;
            margin-top: 16px;
        }




    .content-data .data-expand .full-image {
        width: 100%;
        height: 38%;
        margin-top: 2%;
    }
    .full-image h3 {
        margin: 0;
    }
       .full-image .album-img {
           width: 100%;
           height: 100%;
           display: flex;
           align-items: center;
           justify-content: space-between;
       }
            .album-img .element-img {
                width: 30%;
                height: auto;
            }






/* width */
::-webkit-scrollbar {
    width: 8px;
}

/* Track */
::-webkit-scrollbar-track {
    background: #f1f1f1;
}

/* Handle */
::-webkit-scrollbar-thumb {
    background: #888;
}

    /* Handle on hover */
    ::-webkit-scrollbar-thumb:hover {
        background: #555;
    }
</style>