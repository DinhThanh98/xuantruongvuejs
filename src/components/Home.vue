<template>
  <div>
    <b-container fluid class="p-0">
      <div class="menu-header">
        <div class="logo">
          <a href="#">
            <b-img :src="require('../assets/images/logo.png')"></b-img>
          </a>
        </div>
        <div class="menu_ d-flex">
          <ul>
            <li><a href="#"> gới thiệu </a></li>
            <li><a href="#"> lĩnh vực hoạt động </a></li>
            <li><a href="#"> dự án </a></li>
            <li><a href="#"> quan hệ cổ đông </a></li>
            <li><a href="#"> tin tức </a></li>
            <li><a href="#"> tuyển dụng </a></li>
          </ul>
          <div class="search-flag">
            <div class="search">
              <b-icon icon="search" aria-hidden="true"></b-icon>
            </div>
            <div class="flag">
              <b-img :src="require('../assets/images/vn.png')"></b-img>
              <b-img :src="require('../assets/images/en.png')"></b-img>
            </div>
          </div>
        </div>
      </div>
      <div class="banner-header">
        <VueSlickCarousel v-bind="bannerHome">
            <div class="slick-banner">
              <b-img class="hover" :src="require('../assets/images/project7.jpg')"></b-img>
            </div>
            <div class="slick-banner">
              <b-img class="hover" :src="require('../assets/images/project6.jpg')"></b-img>
            </div>
        </VueSlickCarousel>
        <div class="text-content text-content-section">
          <div class="title">
            <div class="d-flex ">
              <b-img :src="require('../assets/images/star.png')"></b-img>
              <h5>
                CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG VÀ PHÁT TRIỂN XUÂN TRƯỜNG
              </h5>
            </div>
            <h3>Phát triển nguồn năng lượng xanh cho tương lai bền vững</h3>
          </div>
          <div class="button-view">
            <a class="sk-btn sk-btn-1" href="#">
              <span>
                <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')"></b-img>
                <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')"></b-img>
              </span>
              Xem thêm
            </a>
          </div>
        </div>
      </div>
      <div class="section_">
        <b-row>
          <b-col cols="5">
            <div class="banner-left">
              <div class="text-content-section">
                <div class="title">
                  <div class="d-flex ">
                    <h5>
                      <b-img :src="require('../assets/images/star.png')"></b-img>
                      CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG VÀ PHÁT TRIỂN XUÂN TRƯỜNG
                    </h5>
                  </div>
                  <h3>
                    Phát triển nguồn năng lượng xanh cho tương lai bền vững
                  </h3>
                </div>
                <div class="button-view">
                  <a class="sk-btn sk-btn-1" href="#">
                    <span>
                      <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')"></b-img>
                      <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')"></b-img>
                    </span>
                    Xem thêm
                  </a>
                </div>
              </div>
            </div>
          </b-col>
          <b-col cols="7 hight-default">
            <div class="content-right d-flex">
              <div class="text">
                <h3 class="title">Về Xuân Trường</h3>
                <div class="content">
                  <p>
                    Công ty Cổ phần Đầu tư Xây dựng và Phát triển Xuân Trường
                    là đơn vị chuyên nghiệp về đầu tư và xây dựng các công trình
                    năng lượng như thuỷ điện, năng lượng mặt trời, năng lượng
                    gió.
                  </p>
                  <p>
                    Trải qua hơn 1 thập kỷ, với kinh nghiệm và quan hệ với những
                    đối tác lớn hàng đầu, Công ty liên tục nghiên cứu và đầu tư
                    mới vào các dự án năng lượng tái tạo khác trên phạm vi cả
                    nước. Mục tiêu 5 năm tới trở thành đơn vị phát triển năng
                    lượng tái tạo hàng đầu Việt Nam.
                  </p>
                </div>
                <div class="sk-button">
                  <a class="sk-btn sk-btn-1" href="#">
                    <span>
                      <b-img class="default" :src="require('../assets/images/icon-download-blue.png')
                        "></b-img>
                      <b-img class="hover" :src="require('../assets/images/icon-download-white.png')
                        "></b-img>
                    </span>
                    Xuân Trường Profile
                  </a>
                </div>
              </div>
              <div class="images">
                <b-img :src="require('../assets/images/final-02-1578021735-1024x738.jpg')
                  "></b-img>
              </div>
            </div>
          </b-col>
        </b-row>
      </div>
      <div class="section_ section-sumenh">
        <b-row>
          <b-col cols="5">
            <div class="banner-left">
              <div class="text-content-section">
                <div class="title">
                  <div class="d-flex ">
                    <h5>
                      <b-img :src="require('../assets/images/star.png')"></b-img>
                      XÂY NHỮNG GIÁ TRỊ, DỰNG NHỮNG ƯỚC MƠ
                    </h5>
                  </div>
                  <h3>Xây Những Giá Trị, Dựng Những Ước Mơ</h3>
                  <p>
                    Công ty Cổ phần Đầu tư và xây lắp Xuân Trường là doanh
                    nghiệp cổ phần được chuyển đổi từ Công ty TNHH MTV Trường
                    Thành.
                  </p>
                </div>
                <div class="button-view">
                  <a class="sk-btn sk-btn-1" href="#">
                    <span>
                      <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')"></b-img>
                      <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')"></b-img>
                    </span>
                    Xem thêm
                  </a>
                </div>
              </div>
            </div>
          </b-col>
          <b-col cols="7 hight-default">
            <div class="content-right d-flex">
              <div class="about-content d-flex">
                <div class="text">
                  <h3 class="title">
                    <b-img class="default" :src="require('../assets/images/icons1.png')"></b-img>
                    Sứ mệnh
                  </h3>
                  <div class="content">
                    <p>
                      “Phát triển nguồn năng lượng xanh cho một tương lai bền
                      vững là sứ mệnh của Xuân Trường Group.”
                    </p>
                  </div>
                </div>
                <div class="text-images">
                  <div class="images">
                    <b-img :src="require('../assets/images/Ho-Bau-Ngu-cover.jpg')"></b-img>
                  </div>
                  <div class="text_right">
                    <h3 class="title">
                      <b-img class="default" :src="require('../assets/images/icons2.png')"></b-img>
                      Tầm nhìn
                    </h3>
                    <p>
                       Xuân“Trường Group quyết tâm trở thành tập đoàn phát
                      triển hệ sinh thái năng lượng xanh hàng đầu Việt Nam và
                      khu vực, không ngừng học hỏi và sáng tạo, luôn đi đầu
                      trong việc ứng dụng công nghệ mới để kiến tạo hệ sinh thái
                      năng lượng xanh, góp phần hạn chế biến đổi khí hậu, bảo vệ
                      môi trường và nâng tầm vị thế của thương hiệu Việt trên
                      trường quốc tế, trở thành Doanh nghiệp mang tầm cỡ Quốc
                      gia.”
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </b-col>
        </b-row>
      </div>
      <div class="section_ section-about">
        <b-row>
          <b-col cols="5">
            <div class="banner-left">
              <div class="text-content-section">
                <div class="title">
                  <div class="d-flex ">
                    <h5>
                      <b-img :src="require('../assets/images/star.png')"></b-img>
                      ABOUT US
                    </h5>
                  </div>
                  <h3>Về chúng tôi</h3>
                  <p>
                    Công ty Cổ phần Đầu tư và xây lắp Xuân Trường là doanh
                    nghiệp cổ phần được chuyển đổi từ Công ty TNHH MTV Trường
                    Thành.
                  </p>
                </div>
                <div class="button-view">
                  <a class="sk-btn sk-btn-1" href="#">
                    <span>
                      <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')"></b-img>
                      <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')"></b-img>
                    </span>
                    Xem thêm
                  </a>
                </div>
              </div>
            </div>
          </b-col>
          <b-col cols="7 ">
              <h3 class="title" Xuân>Trường Group TV</h3>
              <VueSlickCarousel v-bind="settingsAbout" class="slick-section-about">
                <div class="swiper-slide">
                  <div class="image">
                    <b-img class="hover" :src="require('../assets/images/youtube.jpg')"></b-img>
                  </div>
                  <div class="sk-video-play">
                    <a href="https://www.youtube.com/watch?v=AEHfRfb6rsM&feature=emb_title">
                      <span>
                        <b-img class="hover" :src="require('../assets/images/icon-play.png')"></b-img>
                      </span>
                    </a>
                  </div>
                  <div class="background"></div>
                </div>
                <div class="swiper-slide">
                  <div class="image">
                    <b-img class="hover" :src="require('../assets/images/youtube.jpg')"></b-img>
                  </div>
                  <div class="sk-video-play">
                    <a href="https://www.youtube.com/watch?v=AEHfRfb6rsM&feature=emb_title">
                      <span>
                        <b-img class="hover" :src="require('../assets/images/icon-play.png')"></b-img>
                      </span>
                    </a>
                  </div>
                  <div class="background"></div>
                </div>
              </VueSlickCarousel>
          </b-col>
        </b-row>
      </div>
      <div class="section_ section-about-vision">
        <b-row>
          <b-col cols="5">
            <div class="banner-left">
              <div class="text-content-section">
                <div class="title">
                  <div class="d-flex ">
                    <h5>
                      <b-img :src="require('../assets/images/star.png')"></b-img>
                      ABOUT US
                    </h5>
                  </div>
                  <h3>Sứ mệnh & tầm nhìn</h3>
                  <p>
                    Công ty Cổ phần Đầu tư và xây lắp Xuân Trường là doanh
                    nghiệp cổ phần được chuyển đổi từ Công ty TNHH MTV Trường
                    Thành.
                  </p>
                </div>
                <div class="button-view">
                  <a class="sk-btn sk-btn-1" href="#">
                    <span>
                      <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')"></b-img>
                      <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')"></b-img>
                    </span>
                    Xem thêm
                  </a>
                </div>
              </div>
            </div>
          </b-col>
          <b-col cols="7 ">
            <VueSlickCarousel v-bind="settingsNews" class="slick-section-about">
              <div class="content-new">
                <b-row>
                  <b-col cols="12"><h3 class="title pb-3">Tin tức</h3></b-col>
                  <b-col cols="6">
                    <div class="big-new">
                      <div class="images-new">
                        <b-img class="default" :src="require('../assets/images/z2265403739225_01cfaa40494e07911fff673d827b0756.jpg')
                          "></b-img>
                      </div>
                      <div class="text-new">
                        <h5 class="title">
                          Suất đầu tư liên quan tới điện khí, điện gió, mặt trời
                          trên thế giới (cập nhật tháng 10/2023)
                        </h5>
                        <span>17/10/2023</span>
                        <P>Liên quan tới suất đầu tư một số nguồn điện, chuyên gia
                          Tạp chí Năng lượng Việt Nam cập nhật thông tin về suất
                          đầu tư thuộc lĩnh vực điện khí, điện gió và điện mặt
                          trời trên thế giới hiện nay để bạn đọc cùng tham khảo.
                          Suất đầu...</P>
                        <div class="button-view">
                          <a class="sk-btn sk-btn-1" href="#">
                            <span>
                              <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                                "></b-img>
                              <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                                "></b-img>
                            </span>
                            Xem thêm
                          </a>
                        </div>
                      </div>
                    </div>
                  </b-col>
                  <b-col cols="6">
                    <div class="smalls-new">
                      <div class=" small-new">
                        <div class="images-new">
                          <b-img :src="require('../assets/images/Dien-MT-TQ-1.jpg')"></b-img>
                        </div>
                        <div class="text-new">
                          <h5 class="title">
                            Suất đầu tư liên quan tới điện khí, điện gió, mặt trời
                            trên thế giới (cập nhật tháng 10/2023)
                          </h5>
                          <span>17/10/2023</span>
                          <div class="content-bottom">
                            <P>Liên quan tới suất đầu tư một số nguồn điện, chuyên
                              gia Tạp chí Năng lượng Việt Nam cập nhật thông tin
                              về suất đầu tư thuộc lĩnh vực điện khí, điện gió và
                              điện mặt trời trên thế giới hiện nay để bạn đọc cùng
                              tham khảo. Suất đầu...</P>
                            <div class="button-view">
                              <a class="sk-btn sk-btn-1" href="#">
                                <span>
                                  <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                                    "></b-img>
                                  <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                                    "></b-img>
                                </span>
                                Xem thêm
                              </a>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class=" small-new">
                        <div class="images-new">
                          <b-img :src="require('../assets/images/dien-gio-ngoai-khoi.jpeg')
                            "></b-img>
                        </div>
                        <div class="text-new">
                          <h5 class="title">
                            Suất đầu tư liên quan tới điện khí, điện gió, mặt trời
                            trên thế giới (cập nhật tháng 10/2023)
                          </h5>
                          <span>17/10/2023</span>
                          <div class="content-bottom">
                            <P>Liên quan tới suất đầu tư một số nguồn điện, chuyên
                              gia Tạp chí Năng lượng Việt Nam cập nhật thông tin
                              về suất đầu tư thuộc lĩnh vực điện khí, điện gió và
                              điện mặt trời trên thế giới hiện nay để bạn đọc cùng
                              tham khảo. Suất đầu...</P>
                            <div class="button-view">
                              <a class="sk-btn sk-btn-1" href="#">
                                <span>
                                  <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                                    "></b-img>
                                  <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                                    "></b-img>
                                </span>
                                Xem thêm
                              </a>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </b-col>
                </b-row>
              </div>
              <div class="content-new">
                <b-row>
                  <b-col cols="12"><h3 class="title pb-3">Tin tức</h3></b-col>
                  <b-col cols="6">
                    <div class="big-new">
                      <div class="images-new">
                        <b-img class="default" :src="require('../assets/images/z2265403739225_01cfaa40494e07911fff673d827b0756.jpg')
                          "></b-img>
                      </div>
                      <div class="text-new">
                        <h5 class="title">
                          Suất đầu tư liên quan tới điện khí, điện gió, mặt trời
                          trên thế giới (cập nhật tháng 10/2023)
                        </h5>
                        <span>17/10/2023</span>
                        <P>Liên quan tới suất đầu tư một số nguồn điện, chuyên gia
                          Tạp chí Năng lượng Việt Nam cập nhật thông tin về suất
                          đầu tư thuộc lĩnh vực điện khí, điện gió và điện mặt
                          trời trên thế giới hiện nay để bạn đọc cùng tham khảo.
                          Suất đầu...</P>
                        <div class="button-view">
                          <a class="sk-btn sk-btn-1" href="#">
                            <span>
                              <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                                "></b-img>
                              <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                                "></b-img>
                            </span>
                            Xem thêm
                          </a>
                        </div>
                      </div>
                    </div>
                  </b-col>
                  <b-col cols="6">
                    <div class="smalls-new">
                      <div class=" small-new">
                        <div class="images-new">
                          <b-img :src="require('../assets/images/Dien-MT-TQ-1.jpg')"></b-img>
                        </div>
                        <div class="text-new">
                          <h5 class="title">
                            Suất đầu tư liên quan tới điện khí, điện gió, mặt trời
                            trên thế giới (cập nhật tháng 10/2023)
                          </h5>
                          <span>17/10/2023</span>
                          <div class="content-bottom">
                            <P>Liên quan tới suất đầu tư một số nguồn điện, chuyên
                              gia Tạp chí Năng lượng Việt Nam cập nhật thông tin
                              về suất đầu tư thuộc lĩnh vực điện khí, điện gió và
                              điện mặt trời trên thế giới hiện nay để bạn đọc cùng
                              tham khảo. Suất đầu...</P>
                            <div class="button-view">
                              <a class="sk-btn sk-btn-1" href="#">
                                <span>
                                  <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                                    "></b-img>
                                  <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                                    "></b-img>
                                </span>
                                Xem thêm
                              </a>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div class=" small-new">
                        <div class="images-new">
                          <b-img :src="require('../assets/images/dien-gio-ngoai-khoi.jpeg')
                            "></b-img>
                        </div>
                        <div class="text-new">
                          <h5 class="title">
                            Suất đầu tư liên quan tới điện khí, điện gió, mặt trời
                            trên thế giới (cập nhật tháng 10/2023)
                          </h5>
                          <span>17/10/2023</span>
                          <div class="content-bottom">
                            <P>Liên quan tới suất đầu tư một số nguồn điện, chuyên
                              gia Tạp chí Năng lượng Việt Nam cập nhật thông tin
                              về suất đầu tư thuộc lĩnh vực điện khí, điện gió và
                              điện mặt trời trên thế giới hiện nay để bạn đọc cùng
                              tham khảo. Suất đầu...</P>
                            <div class="button-view">
                              <a class="sk-btn sk-btn-1" href="#">
                                <span>
                                  <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                                    "></b-img>
                                  <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                                    "></b-img>
                                </span>
                                Xem thêm
                              </a>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </b-col>
                </b-row>
              </div>
            </VueSlickCarousel>
          </b-col>
        </b-row>
      </div>
      <div class="section_ section-about-active">
        <b-row>
          <b-col cols="5">
            <div class="banner-left">
              <div class="text-content-section">
                <div class="title">
                  <div class="d-flex ">
                    <h5>
                      <b-img :src="require('../assets/images/star.png')"></b-img>
                      ABOUT US
                    </h5>
                  </div>
                  <h3>Xuân Trường TV</h3>
                  <p>
                    Công ty Cổ phần Đầu tư và xây lắp Xuân Trường là doanh
                    nghiệp cổ phần được chuyển đổi từ Công ty TNHH MTV Trường
                    Thành.
                  </p>
                </div>
                <div class="button-view">
                  <a class="sk-btn sk-btn-1" href="#">
                    <span>
                      <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')"></b-img>
                      <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')"></b-img>
                    </span>
                    Xem thêm
                  </a>
                </div>
              </div>
            </div>
          </b-col>
          <b-col cols="7 hight-default">
            <b-row class="content-new">
              <b-col cols="12">
                <h3 class="title">Hoạt Động Cộng Đồng</h3>
              </b-col>
              <b-col cols="6">
                <div class="item-new">
                  <div class="image">
                    <a href="#">
                      <b-img :src="require('../assets/images/Ung-ho-vaccine-Covid-768x555.jpg')
                        "></b-img>
                    </a>
                  </div>
                  <div class="text">
                    <a href="#">Xuân Trường ủy hộ mua vaccine phòng ngừa Covid-19</a>
                  </div>
                </div>
              </b-col>
              <b-col cols="6">
                <div class="item-new">
                  <div class="image">
                    <a href="#">
                      <b-img :src="require('../assets/images/Ung-ho-vaccine-Covid-768x555.jpg')
                        "></b-img>
                    </a>
                  </div>
                  <div class="text">
                    <a href="#">Lễ công bố Quyết định thành lập chi bộ chi nhánh công ty
                      Xuân Trường tại Ninh Thuận</a>
                  </div>
                </div>
              </b-col>
              <b-col cols="12">
                <div class="sk-button">
                  <a class="sk-btn sk-btn-1" href="#">
                    <span>
                      <b-img class="default" :src="require('../assets/images/arrow-bg-blue-right.png')
                        "></b-img>
                      <b-img class="hover" :src="require('../assets/images/arrow-bg-white-right.png')
                        "></b-img>
                    </span>
                    Xuân Trường Profile
                  </a>
                </div>
              </b-col>
            </b-row>
          </b-col>
        </b-row>
      </div>
      <div class="section-field-activity">
        <div class="hight-default ">
          <b-row>
            <b-col cols="12">
              <h3 class="title">Lĩnh vực hoạt động</h3>
            </b-col>
            <b-col cols="4">
              <div class="item-new">
                <div class="image">
                  <b-img :src="require('../assets/images/item1.jpg')"></b-img>
                </div>
                <div class="content-item">
                  <div class="title">
                    <b-img :src="require('../assets/images/icon-category1.png')" />
                    <h5>Thuỷ điện</h5>
                  </div>
                  <div class="button-view">
                    <a class="sk-btn sk-btn-1" href="#">
                      <span>
                        <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                          "></b-img>
                        <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                          "></b-img>
                      </span>
                      Xem thêm
                    </a>
                  </div>
                </div>
              </div>
            </b-col>
            <b-col cols="4">
              <div class="item-new">
                <div class="image">
                  <b-img :src="require('../assets/images/item2.jpg')"></b-img>
                </div>
                <div class="content-item">
                  <div class="title">
                    <b-img :src="require('../assets/images/icon-category2.png')" />
                    <h5>Điện gió</h5>
                  </div>
                  <div class="button-view">
                    <a class="sk-btn sk-btn-1" href="#">
                      <span>
                        <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                          "></b-img>
                        <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                          "></b-img>
                      </span>
                      Xem thêm
                    </a>
                  </div>
                </div>
              </div>
            </b-col>
            <b-col cols="4">
              <div class="item-new">
                <div class="image">
                  <b-img :src="require('../assets/images/item3.jpg')"></b-img>
                </div>
                <div class="content-item">
                  <div class="title">
                    <b-img :src="require('../assets/images/icon-category3.png')" />
                    <h5>Năng lượng mặt trời</h5>
                  </div>
                  <div class="button-view">
                    <a class="sk-btn sk-btn-1" href="#">
                      <span>
                        <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                          "></b-img>
                        <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                          "></b-img>
                      </span>
                      Xem thêm
                    </a>
                  </div>
                </div>
              </div>
            </b-col>
          </b-row>
        </div>
      </div>
      <div class="section-our-project">
        <div class="hight-default content-new w-100">
          <b-row class="w-100">
            <b-col cols="6 ">
              <div class="item-new-big">
                <div class="image">
                  <b-img :src="require('../assets/images/item4.jpg')"></b-img>
                </div>
                <div class="text-new">
                  <a href="#">
                    <h5 class="title">Nhà máy Thủy điện Ngòi Hút 2</h5>
                  </a>
                  <P>Liên quan tới suất đầu tư một số nguồn điện, chuyên gia Tạp
                    chí Năng lượng Việt Nam cập nhật thông tin về suất đầu tư
                    thuộc lĩnh vực điện khí, điện gió và điện mặt trời trên thế
                    giới hiện nay để bạn đọc cùng tham khảo. Suất đầu...</P>
                  <div class="button-view">
                    <a class="sk-btn sk-btn-1" href="#">
                      <span>
                        <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                          "></b-img>
                        <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                          "></b-img>
                      </span>
                      Xem thêm
                    </a>
                  </div>
                </div>
              </div>
            </b-col>
            <b-col cols="3">
              <div class="smalls-new">
                <div class="small-new">
                  <div class="images-new">
                    <b-img :src="require('../assets/images/item5.jpg')"></b-img>
                  </div>
                  <div class="text-new">
                    <a href="#">
                      <h5 class="title">Nhà máy Thủy điện Ngòi Hút 2A</h5>
                    </a>
                    <div class="content-bottom">
                      <P>Dự án được khởi công vào năm 2015 và hoàn thành vào quý
                        IV năm 2016, với tổng mức đầu tư 292 tỷ đồng, được xây
                        dựng trên diện tích đất 13,5 ha, tại huyện Mù Căng Chải,
                        tỉnh Yên Bái. Nhà máy thủy điện Ngòi Hút 2A có 2 tổ máy,
                        công suất 8,4 MWp, cho sản lượng 30 triệu KWh/năm.</P>
                      <div class="button-view">
                        <a class="sk-btn sk-btn-1" href="#">
                          <span>
                            <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                              "></b-img>
                            <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                              "></b-img>
                          </span>
                          Xem thêm
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="small-new">
                  <div class="images-new">
                    <b-img :src="require('../assets/images/item6.jpg')"></b-img>
                  </div>
                  <div class="text-new">
                    <a href="#">
                      <h5 class="title">Trang trại Điện gió Phương Mai 1</h5>
                    </a>
                    <div class="content-bottom">
                      <P>Dự án Trang trại điện mặt trời Hồ Bầu Ngứ được khởi
                        công vào tháng 03/2018 lắp đặt gần 190.000 tấm pin năng
                        lượng mặt trời, đóng điện và hòa lưới điện quốc gia vào
                        quý IV năm 2019, với tổng vốn đầu tư 1.457 tỷ đồng. Dự
                        án xây dựng trên diện tích 75ha tại huyện Ninh Phước và
                        huyện Thuận Nam, tỉnh Ninh Thuận, với công suất thiết kế
                        là trên 61,77 MWp, cho sản lượng 98 triệu KWh/năm.</P>
                      <div class="button-view">
                        <a class="sk-btn sk-btn-1" href="#">
                          <span>
                            <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                              "></b-img>
                            <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                              "></b-img>
                          </span>
                          Xem thêm
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </b-col>
            <b-col cols="3">
              <div class="smalls-new">
                <div class="small-new">
                  <div class="images-new">
                    <b-img :src="require('../assets/images/item7.jpg')"></b-img>
                  </div>
                  <div class="text-new">
                    <a href="#">
                      <h5 class="title">Trang trại Điện mặt trời Hồ Bầu Ngứ</h5>
                    </a>
                    <div class="content-bottom">
                      <P>Dự án Trang trại điện mặt trời Hồ Bầu Ngứ được khởi
                        công vào tháng 03/2018 lắp đặt gần 190.000 tấm pin năng
                        lượng mặt trời, đóng điện và hòa lưới điện quốc gia vào
                        quý IV năm 2019, với tổng vốn đầu tư 1.457 tỷ đồng. Dự
                        án xây dựng trên diện tích 75ha tại huyện Ninh Phước và
                        huyện Thuận Nam, tỉnh Ninh Thuận, với công suất thiết kế
                        là trên 61,77 MWp, cho sản lượng 98 triệu KWh/năm.</P>
                      <div class="button-view">
                        <a class="sk-btn sk-btn-1" href="#">
                          <span>
                            <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                              "></b-img>
                            <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                              "></b-img>
                          </span>
                          Xem thêm
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="small-new">
                  <div class="images-new">
                    <b-img :src="require('../assets/images/item8.jpg')"></b-img>
                  </div>
                  <div class="text-new">
                    <a href="#">
                      <h5 class="title">Nhà máy Thuỷ điện Pá Hu</h5>
                    </a>
                    <div class="content-bottom">
                      <P>Dự án Nhà máy thủy điện Pá Hú, được tỉnh Yên Bái chấp
                        thuận đầu tư xây dựng vào tháng 03/2017 và đã đóng điện
                        vào tháng 10/2020, tại địa bàn huyện Trạm Tấu, tỉnh Yên
                        Bái, với 2 tổ máy chính, công suất thiết kế là 26 MWp,
                        cho sản lượng điện 90 triệu KWh/năm, và có tổng mức đầu
                        tư trên 1.024 tỷ đồng.</P>
                      <div class="button-view">
                        <a class="sk-btn sk-btn-1" href="#">
                          <span>
                            <b-img class="default" :src="require('../assets/images/arrow-blue-right.png')
                              "></b-img>
                            <b-img class="hover" :src="require('../assets/images/arrow-white-right.png')
                              "></b-img>
                          </span>
                          Xem thêm
                        </a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </b-col>
          </b-row>
        </div>
      </div>
      <div class="section-customers-partners">
        <h3 class="title">Khách hàng và đối tác</h3>
        <VueSlickCarousel v-bind="settings">
          <div>
            <div class="item-slick">
              <b-img :src="require('../assets/images/Logo-BIDV.jpg')"></b-img>
            </div>
          </div>
          <div>
            <div class="item-slick">
              <b-img :src="require('../assets/images/General_Electric_logo.svg.png')"></b-img>
            </div>
          </div>
          <div>
            <div class="item-slick">
              <b-img :src="require('../assets/images/Screen-Shot-2020-01-12-at-8.41.10-PM.jpg')
                "></b-img>
            </div>
          </div>
          <div>
            <div class="item-slick">
              <b-img :src="require('../assets/images/evn.jpg')"></b-img>
            </div>
          </div>
          <div>
            <div class="item-slick">
              <b-img :src="require('../assets/images/agribank-logo.png')"></b-img>
            </div>
          </div>
          <div>
            <div class="item-slick">
              <b-img :src="require('../assets/images/Canadian-Solar-Logo.jpg')"></b-img>
            </div>
          </div>
        </VueSlickCarousel>
      </div>
      <div class="section-footer">
        <b-row>
          <b-col cols="12">
            <div class="logo-footer">
              <b-img :src="require('../assets/images/logo.png')"></b-img>
            </div>
          </b-col>
          <b-col cols="5">
            <div class="textwidget custom-html-widget">
              <h6 class="sk-theme-color">
                CÔNG TY CỔ PHẦN ĐẦU TƯ XÂY DỰNG VÀ PHÁT TRIỂN XUÂN TRƯỜNG
              </h6>
              <div class="footer-info-contact">
                <div class="item">
                  <label>Trụ sở chính: </label>
                  Thôn Nậm Cưởm, Xã Nậm Búng, Huyện Văn Chấn, Yên Bái
                </div>
                <div class="item">
                  <label>Địa chỉ văn phòng Hà Nội: </label>
                  29 Nguyễn Quốc Trị, Trung Hoà, Cầu Giấy, Hà Nội
                </div>
                <div class="item">
                  <label>Điện thoại: </label>
                  02462 691 699
                </div>
                <div class="item">
                  <label>Email: </label>
                  contact@truongthanhgroup.com.vn
                </div>
              </div>
            </div>
          </b-col>
          <b-col cols="4">
            <div class="footer-contact">
              <div class="tex">
                <h5 class="title">Liên hệ với chúng tôi</h5>
                <p>Chúng tôi sẽ liên hệ lại với bạn trong vòng 24h</p>
              </div>
              <div>
                <b-form @submit="onSubmit">
                  <b-form-group id="input-group-2" label="" label-for="input-2">
                    <b-form-input id="input-2" v-model="form.name" placeholder="Họ và Tên" required></b-form-input>
                  </b-form-group>
                  <b-form-group id="input-group-1" label="" label-for="input-1">
                    <b-form-input id="input-1" v-model="form.email" type="email" placeholder="Địa chỉ Email"
                      required></b-form-input>
                  </b-form-group>
                  <b-form-group id="input-group-3" label="">
                    <b-form-input id="input-3" v-model="form.phoneNumber" type="number" placeholder="Số điện thoại"
                      required></b-form-input>
                  </b-form-group>
                  <b-form-textarea id="textarea" v-model="form.content" placeholder="Nội dung/Yêu cầu" rows="3"
                    max-rows="6"></b-form-textarea>
                  <b-button type="submit" variant="primary">Gửi Đi</b-button>
                </b-form>
              </div>
            </div>
          </b-col>
          <b-col cols="3">
            <div class="social-footer footer-contact">
              <h5 class="title">Liên kết mạng xã hội</h5>
            </div>
          </b-col>
        </b-row>
      </div>
    </b-container>
  </div>
</template>
<script>
import VueSlickCarousel from 'vue-slick-carousel'
import {
  BCard,
  BRow,
  BCol,
  BFormInput,
  BButton,
  BTable,
  BMedia,
  BAvatar,
  BLink,
  BBadge,
  BDropdown,
  BDropdownItem,
  BPagination,
  BTooltip,
  BModal,
  BFormCheckbox,
  BFormGroup,
  BFormSelect,
  BAlert
} from 'bootstrap-vue'
// import { getIdFromURL } from 'vue-youtube-embed'
// var videoId = getIdFromURL('https://www.youtube.com/watch?v=24C8r8JupYY')

export default {
  name: 'Home',
  components: {
    VueSlickCarousel,
    BCard,
    BRow,
    BCol,
    BFormInput,
    BButton,
    BTable,
    BMedia,
    BAvatar,
    BLink,
    BBadge,
    BDropdown,
    BDropdownItem,
    BPagination,
    BTooltip,
    BModal,
    BFormGroup,
    BFormCheckbox,
    BFormSelect,
    BAlert
  },
  data () {
    return {
      videoId: 'https://www.youtube.com/watch?v=WLc5-k3y_Po',
      value: '',
      context: null,
      slide: 0,
      sliding: null,
      settings: {
        dots: false,
        infinite: true,
        initialSlide: 2,
        speed: 500,
        slidesToShow: 6,
        slidesToScroll: 1,
        swipeToSlide: true,
        autoplay: true,
        autoplaySpeed: 3000,
        responsive: [
          {
            breakpoint: 1023,
            settings: {
              slidesToShow: 3,
              slidesToScroll: 3
            }
          }
        ]
      },
      settingsAbout: {
        dots: true,
        infinite: true,
        initialSlide: 2,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
        swipeToSlide: true
      },
      settingsNews: {
        dots: true,
        infinite: true,
        initialSlide: 2,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
        swipeToSlide: true,
        centerPadding: '700px',
        'otsClass': 'slick-dots custom-dot-class'
      },
      bannerHome: {
        dots: false,
        infinite: true,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
        autoplay: false,
        swipeToSlide: true,
        edgeFriction: 0.35,
        'otsClass': 'slick-dots custom-dot-class'
      },

      form: {
        email: '',
        name: '',
        phoneNumber: '',
        content: ''
      }
    }
  },
  methods: {
    onSubmit (event) {
      event.preventDefault()
      alert(JSON.stringify(this.form))
    }
  }
}
</script>
<style>
@import "../assets/styles/reset.css";
@import "../assets/styles/home.css";
@import "../assets/styles/reponsive.css";

ul {
  list-style: none;
  margin: unset;
}

a {
  text-decoration: none;
  /* color: white; */
}

.sk-btn {
  display: inline-block;
  height: 46px;
  line-height: 44px;
  padding: 0 25px 0 60px;
  border: 1px #fff solid;
  background: rgba(255, 255, 255, 0.16);
  -webkit-border-radius: 23px;
  border-radius: 23px;
  color: #fff;
  position: relative;
  -webkit-transition: all 0.3s ease-in-out;
  transition: all 0.3s ease-in-out;
  white-space: nowrap;
}

.sk-btn span {
  display: -webkit-flex;
  display: flex;
  -webkit-justify-content: center;
  justify-content: center;
  -webkit-align-items: center;
  align-items: center;
  position: absolute;
  width: 39px;
  height: 39px;
  top: 2px;
  right: calc(100% - 41px);
  line-height: 37px;
  text-align: center;
  -webkit-border-radius: 50%;
  border-radius: 50%;
  background: #fff;
  border: 1px #fff solid;
  -webkit-transition: all 0.3s ease-in-out;
  transition: all 0.3s ease-in-out;
}

.sk-btn img {
  display: inline-block;
  width: auto !important;
  margin: 0 auto;
}

.sk-btn img.hover {
  display: none;
}

.sk-btn:hover {
  background: #fff;
  color: #1b5b23;
  padding: 0 60px 0 25px;
}

.sk-btn:hover span {
  background: #1b5b23;
  right: 2px;
}

.sk-btn:hover img.default {
  display: none;
}

.sk-btn:hover img.hover {
  display: inline-block;
}

.sk-button .sk-btn:hover {
  color: #fff;
  background: #618565;
}

.sk-button .sk-btn {
  color: #1b5b23;
  background: #d7e3d8;
}
</style>
