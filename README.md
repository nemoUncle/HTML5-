# HTML5-
<header>
        <h1>HTML5新增主体结构总结</h1>
        <aside>在HTML5中，为了使文档的结构更加清晰明确，追加了几个页眉、页脚、内容区块等文档结构相关联的结构元素。</aside>
    </header>
    <main>
        <section>
            <article>
                <section><h2>1、article元素</h2></section>
                <section>
                    <p>
                        <section>（1）article元素代表文档、页面或应用程序中独立的、完整的、可以独自被外部引用的内容；</section>
                        <section>（2）一个article元素通常有他自己的标题，有时候还有自己的脚注；</section>
                        <section>（3）article元素可以嵌套使用，内层的内容在原则上需要与外层内容关联；</section>
                        <section>（4）另外article元素也可以用来表示插件，他的作用是使插件看起来好像内嵌在页面当中。</section>
                    </p>
                </section>
            </article>
        </section>
        <section>
            <article>
                <section><h2>2、section元素</h2></section>
                <section>
                    <p>
                        <section>（1）section元素用来对网站或应用程序中页面上的内容进行分块，一个section元素通常由内容及标题组成。</section>
                        <section>（2）section元素并非一个普通的容器元素。当一个容器元素需要直接定义样式或通过脚本定义行为时，应该使用div而非section</section>
                        <section>（3）一般没有标题的内容不使用section</section>
                        <section>（4）section元素的作用是对页面上的内容进行分块，或者说对文章进行分段，不要将他与表示有着自己完整内容的article元素混淆。</section>
                        <section>（5）article元素可以看成是一种特殊类型section元素，它比section元素更强调独立性</section>
                    </p>
                </section>
            </article>
        </section>
        <section>
            <article>
                <section><h2>3、nav元素</h2></section>
                <section>
                    <p>
                        <section>（1）nav元素输一个可以用来作为页面导航的链接组，其中的导航元素链接到其他页面或当前页面的其他部分。</section>
                        <section>（2）并不是所有的链接组都要放进nav元素中，只需要将主要的。基本的链接组放进nav元素中即可。</section>
                        <section>（3）具体来说nav可以用在以下场合：传统导航条；侧边栏单行条；页内导航；翻页操作。</section>
                    </p>
                </section>
                <section>
                    <article>
                        <section><h2>4、aside元素</h2></section>
                        <section>
                            <p>
                                <section>（1）aside元素常用来表示当前页面或文章的附属信息部分，它可以包含当前页面或主要内容相关的引用、侧边栏、广告、导航条、以及其类似的有别于主要内容的</section>
                                <section>（2）aside主要有两种使用方法：
                                    <section>一是：包含在aside元素好中作为主要内容的附属信息部分，其中的内容可以是当前文章有关的参考资料、名词解释等等。</section>
                                    <section>二是：在article之外元素使用，作为页面或者站点全局的附属信息部分。最经典的就是侧边栏，其中的内容是友情链接、博客中其他文章列表或广告单元等。</section>
                                </section>
                            </p>
                        </section>
                    </article>
                </section>
                <section>
                    <article>
                        <section><h2>5、元素与微格式</h2></section>
                        <p>
                            <section>微格式是一种利用HTML的class属性来对网页添加注入新闻事件发生的日期和时间、个人电话号码、企业邮箱之类的附加信息的方法。</section>
                            <section>time元素代表24小时中的某个时刻或者某个日期，表示时刻允许带时差。有很多种格式。
                                <section><time datatime="2016-6-15">2016年6月15日</time></section>
                                <section><time datatime="2016-6-15">6月15日</time></section>
                                <section><time datatime="2016-6-15">我的生日</time></section>
                                <section><time datatime="2016-6-15T20:00">我的生日晚上8点</time></section>
                                <section><time datatime="2016-6-15T20:00Z">我的生日晚上8点</time></section>
                                <section><time datatime="2016-6-15T20:00+09：00">我生日的晚上8点的美国时间</time></section>
                            </section>
                            <section>
                                <h3>pubdata属性</h3>
                                <section>pubdata属性是一个可选的boolean值的属性，它可以被应用到article元素中的time元素上，意思是time元素代表了文章或者整个网页的发布日期。</section>
                            </section>
                        </p>
                    </article>
                </section>
            </article>
        </section>
    </main>
