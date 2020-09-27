<template>
    <div class="labellLst">
        <ul class="list-group">
            <li class="list-group-item">热门标签</li>
            <li class="list-group-item" id="hit-label" v-cloak>
                <span class="btn btn-sm btn-default" v-for="item in labels"> {{item.name}} <i class="badge">{{item.total}}</i></span>
            </li>
        </ul>
    </div>
</template>