<section id="description" class="problem-section">
    <div class="headline">
        <h2>문제</h2>
    </div>
    <div id="problem_description" class="problem-text">
        <p>그래프를 DFS로 탐색한 결과와 BFS로 탐색한 결과를 출력하는 프로그램을 작성하시오. 단, 방문할 수 있는 정점이 여러 개인 경우에는 정점 번호가 작은 것을 먼저 방문하고, 더 이상 방문할 수 있는 점이 없는 경우 종료한다.&nbsp;정점 번호는 1번부터 N번까지이다.</p>
    </div>
</section>

<section id="input" class="problem-section">
    <div class="headline">
        <h2>입력</h2>
    </div>
    <div id="problem_input" class="problem-text">
        <p>첫째 줄에 정점의 개수 N(1 ≤ N ≤ 1,000), 간선의 개수 M(1 ≤ M ≤ 10,000), 탐색을 시작할 정점의 번호 V가 주어진다. 다음 M개의 줄에는 간선이 연결하는 두 정점의 번호가 주어진다. 어떤 두 정점 사이에 여러 개의 간선이 있을 수 있다. 입력으로 주어지는 간선은 양방향이다.</p>
    </div>
</section>

<section id="output" class="problem-section">
    <div class="headline">
        <h2>출력</h2>
    </div>
    <div id="problem_output" class="problem-text">
        <p>첫째 줄에 DFS를 수행한 결과를, 그 다음 줄에는 BFS를 수행한 결과를 출력한다. V부터 방문된 점을 순서대로 출력하면 된다.</p>
    </div>
</section>

<div class="row">
    <div class="col-md-6">
        <section id="sampleinput1">
            <div class="headline">
                <h2>예제 입력 1
                    <button type="button" class="btn btn-link copy-button" style="padding: 0px;" data-clipboard-target="#sample-input-1"></button>
                </h2>
            </div>
            <pre class="sampledata" id="sample-input-1">4 5 1
1 2
1 3
1 4
2 4
3 4
</pre>
        </section>
    </div>
    <div class="col-md-6">
        <section id="sampleoutput1">
            <div class="headline">
                <h2>예제 출력 1
                    <button type="button" class="btn btn-link copy-button" style="padding: 0px;" data-clipboard-target="#sample-output-1"></button>
                </h2>
            </div>
            <pre class="sampledata" id="sample-output-1">1 2 4 3
1 2 3 4
</pre>
        </section>
    </div>
</div>

<div class="row">
    <div class="col-md-6">
        <section id="sampleinput2">
            <div class="headline">
                <h2>예제 입력 2
                    <button type="button" class="btn btn-link copy-button" style="padding: 0px;" data-clipboard-target="#sample-input-2"></button>
                </h2>
            </div>
            <pre class="sampledata" id="sample-input-2">5 5 3
5 4
5 2
1 2
3 4
3 1
</pre>
        </section>
    </div>
    <div class="col-md-6">
        <section id="sampleoutput2">
            <div class="headline">
                <h2>예제 출력 2
                    <button type="button" class="btn btn-link copy-button" style="padding: 0px;" data-clipboard-target="#sample-output-2"></button>
                </h2>
            </div>
            <pre class="sampledata" id="sample-output-2">3 1 2 5 4
3 1 4 2 5
</pre>
        </section>
    </div>
</div>

<div class="row">
    <div class="col-md-6">
        <section id="sampleinput3">
            <div class="headline">
                <h2>예제 입력 3
                    <button type="button" class="btn btn-link copy-button" style="padding: 0px;" data-clipboard-target="#sample-input-3"></button>
                </h2>
            </div>
            <pre class="sampledata" id="sample-input-3">1000 1 1000
999 1000
</pre>
        </section>
    </div>
    <div class="col-md-6">
        <section id="sampleoutput3">
            <div class="headline">
                <h2>예제 출력 3
                    <button type="button" class="btn btn-link copy-button" style="padding: 0px;" data-clipboard-target="#sample-output-3"></button>
                </h2>
            </div>
            <pre class="sampledata" id="sample-output-3">1000 999
1000 999
</pre>
        </section>
    </div>
</div>

<section id="source">
    <div class="headline">
        <h2>출처</h2>
    </div>
    <ul>
        <li>문제를 만든 사람:&nbsp;author5</li>
        <li>데이터를 추가한 사람:&nbsp;dfghcvb11, djm03178, doju</li>
        <li>어색한 표현을 찾은 사람:&nbsp;doju</li>
        <li>빠진 조건을 찾은 사람:&nbsp;pumpyboom</li>
    </ul>
</section>

<section id="problem_tags">
    <div class="headline">
        <h2>알고리즘 분류</h2>
    </div>
    <ul class="spoiler-list">
        <li>그래프 이론</li>
        <li>그래프 탐색</li>
        <li>너비 우선 탐색</li>
        <li>깊이 우선 탐색</li>
    </ul>
</section>
