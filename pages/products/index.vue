<template>
    <div>
        <nuxt-link to="/products/create">新規作成</nuxt-link>

        <table>
            <tr>
                <th>商品番号</th>
                <th>商品名</th>
                <th>詳細</th>
                <th>編集</th>
            </tr>
            <tr>
                <td>1</td>
                <td>テスト</td>
                <td><nuxt-link to="/products/1/show">詳細</nuxt-link></td>
                <td><nuxt-link to="/products/1/edit">編集</nuxt-link></td>
            </tr>
        </table>
    </div>
</template>

<script>
export default {}
</script>