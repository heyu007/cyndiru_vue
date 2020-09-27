<template>
    <div class="author-msg">
        <div class="author" style="background:url('../assets/logo.png')">
            <div class="author-img">
                <img src="../assets/logo.png" alt="">
            </div>
            <p>Cyndieu</p>
        </div>
        <div class="list-group" id="author-info" style="margin-bottom:0">
            <a href="#" class="list-group-item"><span class="glyphicon glyphicon-pencil" aria-hidden="true"></span> {{commit}}</a>
            <a href="#" class="list-group-item"><span class="glyphicon glyphicon-tag" aria-hidden="true"></span> {{label}}</a>
            <a href="#" class="list-group-item"><span class="glyphicon glyphicon-star" aria-hidden="true"></span> {{profession}}</a>
            <a href="#" class="list-group-item"><span class="glyphicon glyphicon-time" aria-hidden="true"></span> {{createtime}}</a>
        </div>
    </div>
</template>