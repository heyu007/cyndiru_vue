<template>
    <div class="about">
        <div class="web-msg" v-cloak>
            <div class="list-group">
                <a href="javascript:" class="list-group-item"> 关于小厄</a>
                <a href="#" class="list-group-item"><span class="glyphicon glyphicon-heart-empty"
                                                          aria-hidden="true"></span> {{love}}</a>
                <a href="#" class="list-group-item"><span class="glyphicon glyphicon-envelope"
                                                          aria-hidden="true"></span> {{email}}</a>
                <a href="#" class="list-group-item"><span class="glyphicon glyphicon-stats"
                                                          aria-hidden="true"></span> {{(open + 1345) * 126}}</a>
                <!--<a href="#" class="list-group-item"><span class="glyphicon glyphicon-user" aria-hidden="true"></span> {{author}}</a>-->
            </div>
        </div>
    </div>
</template>