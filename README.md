# goit-markup-hw-08

homework-8 markup

<!-- Тег picture структура -->

                <picture>
                  <source
                    srcset="
                      ./images/work/box-1_sm@2x.jpg    1x,
                      ./images/work/box-1_sm@2x.jpg 2x
                    "
                    media="(min-width: 1200px)"
                    type="image/jpeg"
                  />
                  <source
                    srcset="
                      ./images/work/box-1_md@2x.jpg    1x,
                      ./images/work/box-1_md@2x.jpg 2x
                    "
                    media="(min-width: 768px)"
                    type="image/jpeg"
                  />
                  <source
                    srcset="./images/work/box-1_lg@2x.jpg 2x"
                    media="(max-width: 767px)"
                    type="image/jpeg"
                  />
                  <img
                  class="work__pic"
                  src="./images/work/box1_lg.jpg"
                  alt="Написание кода"
                  width="370"
                  height="294"
                  />
                </picture>
