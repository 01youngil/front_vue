<template>
    <v-container>
        <v-row>
            <!-- 전체 cols는 12 -->
            <v-col cols="8">
                helloworld1
            </v-col>
            <v-col cols="4">
                helloworld2
            </v-col>
        </v-row>
        <v-row>
            <v-card>
                <v-card-title>
                    회원가입
                </v-card-title>
                <v-card-text>
                    회원가입을 해주세요
                </v-card-text>
            </v-card>
        </v-row>
        <v-row>
            <v-simple-table>
                <thead>
                    <tr>
                        <th>이름</th><th>이메일</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>최영일</td><td>il@naver.com</td>
                    </tr>
                    <tr>
                        <td>최영재</td><td>jae@naver.com</td>
                    </tr>
                </tbody>
            </v-simple-table>
        </v-row>
    </v-container>

    <v-card>
        <v-card-title>
            회원가입
        </v-card-title>
        <v-card-text>
            <v-form>
                <v-text-field
                    label="email"
                    type="email"
                />
                <v-text-field
                    label="name"
                    type="text"
                />
                <v-text-field
                    label="password"
                    type="password"
                />
                <v-btn color="primary">제출하기</v-btn>
            </v-form>
        </v-card-text>
    </v-card>
</template>
<script>
    export default{

    }
</script>