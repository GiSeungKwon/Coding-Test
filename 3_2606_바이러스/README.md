<section id="description" class="problem-section">
    <div class="headline">
        <h2>문제</h2>
    </div>
    <div id="problem_description" class="problem-text">
        <p>신종 바이러스인 웜 바이러스는 네트워크를 통해 전파된다. 한 컴퓨터가 웜 바이러스에 걸리면 그 컴퓨터와 네트워크 상에서 연결되어 있는 모든 컴퓨터는 웜 바이러스에 걸리게 된다.</p>
        <p>예를 들어 7대의 컴퓨터가 &lt;그림 1&gt;과 같이 네트워크 상에서 연결되어 있다고 하자. 1번 컴퓨터가 웜 바이러스에 걸리면 웜 바이러스는 2번과 5번 컴퓨터를 거쳐 3번과 6번 컴퓨터까지 전파되어 2, 3, 5, 6 네 대의 컴퓨터는 웜 바이러스에 걸리게 된다. 하지만 4번과 7번 컴퓨터는 1번 컴퓨터와 네트워크상에서 연결되어 있지 않기 때문에 영향을 받지 않는다.</p>
        <p><img alt="" src="./virus.png" style="width: 239px; height: 157px; "></p>
        <p>어느 날 1번 컴퓨터가 웜 바이러스에 걸렸다. 컴퓨터의 수와 네트워크 상에서 서로 연결되어 있는 정보가 주어질 때, 1번 컴퓨터를 통해 웜 바이러스에 걸리게 되는 컴퓨터의 수를 출력하는 프로그램을 작성하시오.</p>
    </div>
</section>

<section id="input" class="problem-section">
    <div class="headline">
        <h2>입력</h2>
    </div>
    <div id="problem_input" class="problem-text">
        <p>첫째 줄에는 컴퓨터의 수가 주어진다. 컴퓨터의 수는 100 이하인 양의 정수이고 각 컴퓨터에는 1번 부터 차례대로 번호가 매겨진다. 둘째 줄에는 네트워크 상에서 직접 연결되어 있는 컴퓨터 쌍의 수가 주어진다. 이어서 그 수만큼 한 줄에 한 쌍씩 네트워크 상에서 직접 연결되어 있는 컴퓨터의 번호 쌍이 주어진다.</p>
    </div>
</section>

<section id="output" class="problem-section">
    <div class="headline">
        <h2>출력</h2>
    </div>
    <div id="problem_output" class="problem-text">
        <p>1번 컴퓨터가 웜 바이러스에 걸렸을 때, 1번 컴퓨터를 통해 웜 바이러스에 걸리게 되는 컴퓨터의 수를 첫째 줄에 출력한다.</p>
    </div>
</section>

<div class="row">
    <div class="col-md-6">
        <section id="sampleinput1">
            <div class="headline">
                <h2>예제 입력 1
                </h2>
            </div>
            <pre class="sampledata" id="sample-input-1">7
6
1 2
2 3
1 5
5 2
5 6
4 7
</pre>
        </section>
    </div>
    <div class="col-md-6">
        <section id="sampleoutput1">
            <div class="headline">
                <h2>예제 출력 1
                </h2>
            </div>
            <pre class="sampledata" id="sample-output-1">4
</pre>
        </section>
    </div>
</div>

<section id="source">
    <div class="headline">
        <h2>출처</h2>
    </div>
    <p><a>Olympiad</a>&nbsp;&gt;&nbsp;<a>한국정보올림피아드</a>&nbsp;&gt;&nbsp;<a>한국정보올림피아드시․도지역본선</a>&nbsp;&gt;&nbsp;<a>지역본선 2004</a>&nbsp;&gt;&nbsp;<a>초등부</a>&nbsp;3번</p>
    <ul>
        <li>데이터를 추가한 사람:&nbsp;<a>chansol</a>, <a>jh05013</a></li>
        <li>잘못된 데이터를 찾은 사람:&nbsp;<a>djm03178</a>, <a>jsa3824</a></li>
    </ul>
</section>
