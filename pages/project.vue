<template>
  <v-row>
    <div class="box pt-2 pb-2">
      <h2>
        <a href="https://heybirdie.co.kr" target="_blank" rel="noopener"
          >헤이버디 - 나와 맞는 골프 찾기</a
        >
      </h2>
      <hr />
      <h2>헤이버디, 우리의 미션은 골프를 보다 스마트하게!</h2>
      <p>
        골프인들이 함께 만들어가는 서비스, 양질의 정보를 제공하고, 평가를
        공유하며, 분석하여 제공함으로 돈과 시간의 낭비로부터 보호하고자
        합니다.<br />
        이런 멋진 서비스를 만들기위해 시작한 창업 그 여정을 소개합니다.
      </p>
      <p>
        저는 Full-Stack 개발자로 헤이버디의 서비스 전체를 개발을 진행
        하였습니다.<br />개발을 진행하며 겪은 문제와 문제를 해결하는 과정도 함께
        소개합니다.
      </p>
      <a href="https://heybirdie.co.kr" target="_blank" rel="noopener"
        >헤이버디(https://heybirdie.co.kr)</a
      >
      <br />

      <v-simple-table>
        <template #default>
          <tbody>
            <tr>
              <td>이름</td>
              <td>헤이버디</td>
            </tr>
            <tr>
              <td>당담</td>
              <td>Full-Stack 개발</td>
            </tr>
            <tr>
              <td>기간</td>
              <td>2019년 12월 15일 ~ 2021년 12월 31일</td>
            </tr>
            <tr>
              <td>기술스택</td>
              <td>
                NuxtJS, Express, ES6, Sequelize, AWS, RDB, Notion, Zeplin, PWA,
                Lint, CICD, GIT
              </td>
            </tr>
          </tbody>
        </template>
      </v-simple-table>

      <br />
      <h2>어째서 골프인가?</h2>
      <p>
        골프는 이제는 남녀노소 나이와 상관없이 즐길 수 있는 스포츠가 되었습니다.
        옛날과 달리 더는 골프를 배우고 즐기는 데 많은 돈이 들어가지 않으며,
        스크린골프장 등 필드가 아니더라도 다양한 곳에서 간편하게 즐길수 있는
        스프츠입니다. 이렇게 일상과 가까워진 골프지만 미국과 일본 등 해외 골프
        관련 전문 사이트보다 국내의 골프 사이트는 현 모바일 이용자에 대한
        편의성과 최신 추세를 따라가지 못한다고 판단하여 이 시장을 발전시킬
        필요성이 있었습니다.
      </p>
      <br />
      <h2>어떤 문제를 해결 할 것인가?</h2>
      <p>
        가장 기본인 체계적인 정보 제공입니다. <br />골프에 대해 알고 싶어도 입문
        하려 검색을 해도 검색된 결과는 전부 쇼핑몰만 나올 뿐이었습니다. 따라서
        정확한 정보를 분석하여 제공하고자 하였습니다. <br />
        또한 골프채를 고르려고 하여도 골프 매점에서 상담을 받아야만 나와 맞는
        골프채를 찾을 수 있다는 점에도 주목하였습니다. 따라서 골프채 스펙을
        정리한 데이터베이스와 선수들의 데이터베이스를 준비한 뒤 사용자가 자신의
        신체 제품규격 및 골프 스타일만 입력하면 가장 가까운 스타일의 프로선수가
        사용하는 골프채 정보도 제공할 수 있는 서비스를 개발하였습니다. 또한
        리뷰를 통하여 가장 평이 좋은 골프채 및 골프채에 대한 트랜드를 파악할 수
        있도록 제공하였습니다.
      </p>
      <br />
      <h2>헤이버디를 만들어가는 길고 긴 여정</h2>
      <v-img :lazy-src="logo" :src="logo" alt="헤이버디 로고" />
      <p>
        헤이버디라는 이름은 두 가지의 의미를 가지고 지어졌습니다. 친구의 buddy.
        골프에서의 birdie. 사용자와 친근하게 다가가고자 하였고, 이 서비스에서
        많은 것을 얻어 골프에서 좋은 성적을 얻어갈 정보를 찾기를 바랐습니다.
        그렇게 Hey, birdie! 가 되었습니다.
      </p>
      <p>로고 색상은 골프의 상징과 같은 잔디색을 선택하였습니다.</p>

      <v-img
        :lazy-src="color"
        :src="color"
        alt="#1abc9c 색상"
        width="100"
        height="100"
      />

      <p>
        부드러운 파스텔 컬러로 사이트의 이미지를 대표하는 색상으로 전체적인
        사이트 디자인에 많은 부분에서 사용되었습니다.
      </p>
      <br />
      <h2>개발 전략</h2>
      <p>
        헤이버디의 목표와 아이덴티티가 정해지고 난 뒤 새로운 아이디어는 매일매일
        생겨났고 거기에 맞는 개발 전략도 필요하였습니다. 선택한 전략은
        <strong>'린하게 하자'</strong>였습니다. 요구사항을 빠르게 정한 다음
        그거에 맞는 계획을 Notion에서 세부사항을 나눠 정리했습니다. 장단기 OKR을
        설정하였고 목표에 다가가기 위한 단계를 세분화하였습니다.
      </p>
      <v-img
        :lazy-src="notion"
        :src="notion"
        alt="노션 활용한 개발 계획및 프로젝트 관리"
      />
      <p>
        작업내용은 복잡하게 문서화하지 않으며 빠르게 노션을 통해 실시간으로
        현황을 공유하며 작업을 효율화하였습니다.
      </p>
      <p>
        기본적인 준비가 모두 끝나고 프로토타입 제작을 시작하였습니다.<br />
        <a
          href="https://ovenapp.io/view/39Ul1WL1WIHbYUvT6zy3DjatsKjQsPCu/nEq4e"
          rel="noopener"
          target="_blank"
          >프로토타입 보기</a
        ><br />
        프로토타입을 기반으로 화면 계획 및 디자인을 제플린으로 공유되어 왔으며
        신속하게 개발을 진행 할 수 있었습니다. 디자인의 핵심 요소는 시력이 낮은
        분이 이용하더라도 문제가 없도록 글씨는 크게, 화면은 세련되게 그리고
        뉴모피즘을 일부 도입하여 시각적인 재미를 더하고자 하였습니다.
      </p>
      <v-img
        :lazy-src="zeplin"
        :src="zeplin"
        alt="제플린을 통해 화면 계획 및 디자인 공유"
      />
      <h2>개발 시작</h2>
      <p>
        목표, 디자인, 화면 계획이 모두 준비가 되고 드디어 개발을 시작하게
        되었습니다. 스타트업의 핵심 과제는 얼마나 빠르게 아이디어를 적용하고
        시장 반응을 볼 수 있는냐고 생각합니다. 그렇기 위해 적은 러닝타임, 빠른
        개발, 증명된 기술 스택을 중점으로 다음과 같이 구조를 정하였습니다.
      </p>
      <h3>AWS EC2 프론트엔드 서버</h3>
      <p>
        적은 러닝타임과 빠른 개발 증명된 기술 스택으로 가장 적합하다고 생각되는
        프레임워크를 선택하였습니다. 바로 VueJS입니다. SFC 구조로 하나의 파일이
        하나의 컴포넌트가 되기에 프로젝트가 더 간소해지고, template 문법은 기존
        HTML과 크게 다르지 않아 개발하는데도 편리하여 빠른 개발을 가능하게
        하였습니다. 또한 프로그레시브 웹 프레임워크인 만큼 로딩이 없는 빠른
        화면을 제공하기에 사용자 경험을 극도로 개선 할 수 있었습니다.
      </p>
      <h3>AWS EC2 백엔드 서버</h3>
      <p>
        NodeJS의 Express 웹 프레임워크가 사용되었습니다. 초기 구성만 잘
        설계한다면 간단한 문법과 빠른 동작 속도는 이미 여러 기업으로부터 증명된
        레퍼런스를 가지고 있으며 Node 진영에서 가장 많이 사용되는 웹 프레임워크
        이기에 선택 되었습니다.
      </p>
      <h3>AWS RDB 데이터베이스 서버</h3>
      <p>
        초기에는 데이터의 특성상 NoSQL 도입을 고민하였지만, 숙련도와 개발환경
        구성을 위해서 RDBMS를 선택하게 되었습니다. Express와 Sequelize
        라이브러리를 사용함으로 백 엔드를 개발하며 DB 구조 (모델) 정의를
        함께하여 더욱더 빠르고 향후 DB 마이그레이션을 하더라도 큰 문제가
        발생하지 않도록 하게 되었습니다.
      </p>
      <p>
        이런 Monolithic 아키텍쳐 구조는 MSA에 비해 안전성은 떨어지나 소규모의
        개발인력으로도 간단한 설계와 빠른 개발이 가능합니다. 또한 이러한 구조는
        오랜 기간동안 수많은 프로젝트에서 사용되어 왔던만큼 Best Practice를 쉽게
        찾을수 있으며 적용하는데 적은 노력으로도 가능했습니다.
      </p>
      <v-img :lazy-src="heybirdie" :src="heybirdie" alt="헤이버디 메인" />
      <h2>정보 수집은 어떻게?</h2>
      <p>
        아쉽게도 골프와 관련된 정보는 국내에서 얻을 수가 없습니다. 정보가 많지도
        않았으며 잘 정리되어 있지도 공유되어 있지도 않았습니다. 따라서 Python을
        활용하여 특별한 파싱프로그램을 개발하였습니다. 라이센스에 따라 수집부터
        재가공 후 DB에 적재까지 한 번에 되도록 작성된 이 프로그램은 향후 골프채
        평가 부분에서 사용되게 되었습니다. 수집된 데이터와 오픈 API를 조합하여
        다음과 같은 기능을 제공하여 정보를 제공하였습니다. 각각 따로 있던
        데이터들을 퍼즐 맞추듯 하나로 모으니 믿을 수 없을 만큼 유용한 정보가
        되었습니다.
      </p>
      <v-img :lazy-src="review" :src="review" alt="헤이버디 평가 페이지" />
      <h2>수집된 정보를 나와 맞는 골프채 찾기까지로 이어지게...</h2>
      <p>
        평가페이지에서 자세한 정보를 제공하지만 역시 사용자는 골프채 하나하나
        찾아가며 나와 맞는 곮프채를 찾아야만 했었습니다. 따라서 2가지의
        해결방안을 생각했습니다. <br />첫 번째는 예측 가능한 장비 성향을 MPF
        코드로 만들어 장비마다 부여한 뒤 알맞은 골프채를 찾아주는 방법. <br />두
        번째는 나와 비슷한 선수들을 유클리드 디스텐스 알고리즘을 사용하여 찾을
        수 있게 해주는 방법입니다.
      </p>
      <v-img :lazy-src="mpf" :src="mpf" alt="MPF 란?" />
      <v-img
        :lazy-src="distence0"
        :src="distence0"
        alt="유클리드 디스텐스 분석 기법"
      />
      <v-img
        :lazy-src="distence1"
        :src="distence1"
        alt="유클리드 디스텐스 분석 기법"
      />
      <v-img
        :lazy-src="distence2"
        :src="distence2"
        alt="유클리드 디스텐스 분석 기법"
      />
      <h2>2021년 여정의 끝</h2>
      <p>
        헤이버디를 통해 창업과 운영에대해 많은걸 생각할 수 있었습니다.<br />
        또한 많은걸 배울수 있었으며 다음에 준비할 서비스에서는 더욱 유용하며<br />
        탄탄하게 서비스를 준비할수 있도록 많은 성장을 하겠습니다.
      </p>
    </div>
  </v-row>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  scrollToTop: true,
  data() {
    return {
      logo: require('../assets/heybirdie/logo.webp'),
      notion: require('../assets/heybirdie/notion.webp'),
      zeplin: require('../assets/heybirdie/zeplin.webp'),
      heybirdie: require('../assets/heybirdie/heybirdie.co.kr_.webp'),
      review: require('../assets/heybirdie/review.webp'),
      mpf: require('../assets/heybirdie/mpf.webp'),
      distence0: require('../assets/heybirdie/distence0.webp'),
      distence1: require('../assets/heybirdie/distence1.webp'),
      distence2: require('../assets/heybirdie/distence2.webp'),
      color: require('../assets/heybirdie/color.webp'),
    }
  },
  head() {
    return {
      title: '대표 프로젝트',
    }
  },
})
</script>
