<template>
  <div class="container">

    <section class="e1">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e2">
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
    </section>

    <section class="e3">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e4">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e5">
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
    </section>

    <section class="e6">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e7">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e8">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e9">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e10">
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
    </section>

    <section class="e11">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e12">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e13">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e14">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e15">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e16">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e17">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e18">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e19">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e20">
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
      <a href="">
        <span>javascript</span>
      </a>
    </section>

    <section class="e21">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>

    <section class="e22">
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
      <a href="">javascript</a>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus">
  *{
    box-sizing: border-box;
  }
  *::before{
    box-sizing: border-box;
  }
  *::after{
    box-sizing: border-box;
  }
  a {
	position: relative;
	display: inline-block;
	margin: 15px 25px;
	outline: none;
	color: #fff;
	text-decoration: none;
	text-transform: uppercase;
	letter-spacing: 1px;
	font-weight: 400;
	text-shadow: 0 0 1px rgba(255,255,255,0.3);
  font-size: 1.35em;
  }
  a:hover, a:focus{
    outline: none;
  }
  
  .container{
    display: flex;
    align-items: center;
    justify-content: space-around;
    align-content space-around;
    flex-wrap wrap;
  }

  section{
    display: flex;
    align-items: center;
    justify-content: space-around;
    align-content space-around;
    flex-wrap wrap;
    width: calc(100% - 12px);
    height auto;
    padding: 60px 20px;
    margin: 20px;
    border: 6px solid rgba(255,255,255,0.2)
    border-radius: 36px;
    transition: transform 0.5s;
    &:hover{
      transform: scale(1.02);
    }
  }
  section a{
    display: inline-block;
    // width: 25%;
  }

  .e1{
    background: #435a6b;
  }
  .e1 a{
    background #435a6b;
    transition background 1.5s;
  }
  .e1 a::before{
    margin-right: 10px;
    content: '<';
	  transform: translateX(20px);
  }
  .e1 a::after{
    margin-left: 10px;
    content: '>';
	  transform: translateX(-20px);
  }
  .e1 a::before, .e1 a::after{
    display: inline-block;
    opacity: 0;
    transition: transform 0.3s, opacity 2s;
  }
  .e1 a:hover{
    background: orange;
  }
  .e1 a:hover::before, .e1 a:hover::after{
    opacity: 1;
	  transform: translateX(0px);
  }

  .e2{
    background: #0e83cd;
    a{
      perspective: 1000px;
      // backface-visibility visible
      span{
        position relative
        display inline-block
        padding: 5px 15px;
        background: #2195de
        transition transform 0.3s
        transform-origin top
        transform-style preserve-3d
        &::before{
          position absolute
          top 100%
          left 0
          // width 100%
          // height 100%
          padding: 5px 15px;
          background #0965a0
          content 'javascript'
          transition background 1.5s
          transform rotateX(-90deg)
          transform-origin 50% 0
        }
      }
      &:hover{
        span{
          transform rotateX(90deg) translateY(-25px)
          &::before{
            background orange
          }
        }
      }
    }
  }

  .e3{
    background #f19f0f;
    a {
      padding: 8px 0
      &::after{
        position absolute
        content: ''
        width: 100%
        height 4px;
        background-color: rgba(0,0,0,0.2)
        top: 120%
        left: 0
        opacity 0
        transition: opacity 0.3s, top 0.3s
      }
      &:hover::after{
        opacity 1
        top: 100%
      }
    }
  }

  .e4{
    background #3fa46a;
    a {
      padding: 8px 0
      &::after{
        position absolute
        content: ''
        width: 100%
        height 4px;
        background-color: rgba(255,255,255,0.8)
        top: 100%
        left: 0
        opacity 0
        transition: opacity 0.3s, top 0.3s
      }
      &:hover::after{
        opacity 1
        top: 120%
      }
    }
  }

  .e5{
    background #cd4436;
    a {
      overflow hidden
      padding: 0 5px
      span{
        position relative
        display inline-block
        font-weight 100
        transition transform 0.3s
        &::before{
          position absolute
          top 100%
          content "javascript"
          font-weight 700
          color: orange
          transform translate3d(0,0,0)
          transition transform 0.3s, color 0.3s
        }
      }
      &:hover{
        span{
          transform translateY(-100%)
        }
      }
    }
  }

  .e6{
    background #3fa46a;
    a {
      padding: 10px 20px;
      &::before{
        position absolute
        content: ''
        width: 2px
        height 0;
        background-color: #fff;
        top: 0
        left: 0
        transition: opacity 0.3s, top 0.3s, height 0.3s
      }
      &::after{
        position absolute
        content: ''
        width: 100%
        height 2px;
        background-color: #fff;
        top: 0
        left: 0
        transition: opacity 0.3s, top 0.3s
      }
      &:hover {
        &::before{
          height: 100%
        }
        &::after{
          top: 100%
        }
      }
    }
  }

  .e7{
    background #f19f0f;
    a {
      padding: 10px 20px;
      &::before{
        position absolute
        content: ''
        width: 100%
        height 2px;
        background-color: #fff;
        top: 100%
        left: 0
      }
      &::after{
        position absolute
        content: ''
        width: 100%
        height 2px;
        background-color: #fff;
        top: 100%
        left: 0
        opacity: 0
        transition: opacity 0.3s, top 0.3s
      }
      &:hover {
        &::after{
          opacity: 1
          top: 0
        }
      }
    }
  }

  .e8{
    background #3fa46a;
    a {
      padding: 10px 20px;
      transition color 1s
      &::before, &::after{
        position absolute
        content: ''
        top 0
        left: 0
        width: 100%;
        height: 100%
        border: 2px solid #222;
        background: transparent
        transition: top 0.3s, left 0.3s, opacity 0.3s;
      }
      &::after{
        border: 2px solid #fff;
        top: -5%
        left: 5%
        opacity: 0
      }
      &:hover {
        color: orange;
        &::before{
          opacity: 0
          top 0
          left 0
        }
        &::after{
          opacity: 1
          top: 0
          left: 0
        }
      }
    }
  }

  .e9{
    background #f19f0f;
    a {
      padding: 10px 20px;
      transition color 1s
      &::before{
        position absolute
        content: ''
        top -20%
        left: 0
        width: 100%;
        height: 2px
        background: #fff
        transition: height 0.3s
      }
      &::after{
        position absolute
        content: 'javscript'
        font-size: 12px
        font-style:italic
        color: black;
        width: 100%;
        height: 80%
        top 60%
        left: 0
        border-bottom: 2px solid #fff
        padding: 5px
        opacity: 0
        transition: opacity 0.3s, top 0.5s
      }
      &:hover {
        color: #158;
        &::before{
          height: 6px
        }
        &::after{
          opacity: 1
          top: 100%
        }
      }
    }
  }

  .e10{
    background #0e83cd;
    a {
      overflow: hidden
      margin: 0 15px
      span{
        display: block
        padding: 10px 20px;
        color: #ffffff
        background: #0965a0;
        transition: left 0.3s
        &::before{
          position absolute;
          width: 100%
          height: 100%
          padding: 10px 20px;
          content: 'javascript'
          color: #0965a0;
          background: #fff
          top: 0
          left: -100%
          transition left 0.3s
        }
      }
      &:hover{
        span {
          left: 100%
          &::before{
            left: 0
          }
        }
      }
    }
  }

  .e11{
    background: #085247;
    a {
      border-top: 2px solid #0972b8;
      color: #0972b8;
      text-shadow 3px 3px 3px
      padding: 10px 0
      &::before{
        position absolute;
        top 0
        left: 0
        content "javascript"
        height: 100%;
        padding: 10px 0
        width 0
        text-shadow none
        overflow hidden
        border-bottom: 2px solid #fff
        color: #fff
        transition width 0.5s
      }
      &:hover{
        &::before{
          width: 100%
        }
      }
    }
  }

  .e12{
    background #f19f0f;
    a {
      padding: 10px 20px;
      transition color 1s
      &::before, &::after{
        position absolute
        content: ''
        width: 100px
        height: 100px
        border: 2px solid rgba(121,25,36,0.1)
        border-radius 50%
        background: transparent
        top: 50%
        left: 50%
        transform: translate(-50%,-50%) scale(0.2)
        opacity 0
        transition: transform 0.3s, opacity 0.3s
      }
      &::after{
        border:  6px solid rgba(12,125,36,0.2)
        width: 75px
        height: 75px
        transform: translate(-50%, -50%) scale(0.5)
      }
      &:hover {
        color: #fff;
        &::before, &::after{
          transform: translate(-50%, -50%) scale(1.5)
          opacity: 1
        }
      }
    }
  }

  .e13{
    background #3fa46a;
    a {
      padding: 2px 5px;
      transition color 1s
      &::before {
        position absolute
        width: 100%
        height: 24px
        padding: 10px 0
        border-radius: 50%
        content: '•'
        color: #fff
        font-size 20px
        top: 50%
        left: 0
        opacity 0
        transition: text-shadow 0.3s, opacity 0.3s
      }
      &:hover {
        color: yellow
        &::before{
          text-shadow: 15px 0 #fff, -15px 0 #fff
          opacity: 1
        }
      }
    }
  }

  .e14{
    background #685486;
    a {
      padding: 20px
      transition color 1s
      &::before, &::after{
        position absolute
        top: 0
        width: 3px
        height: 100%
        content: ''
        background: #888;
        transition: all 0.3s
      }
      &::before{
        left: -10%
        transition all 0.3s
      }
      &::after {
        right -10%
        transition: all 0.3s
      }
      &:hover {
        color: yellow
        &::before{
          transform: rotate(90deg)
          left: 50%
          top: -50%
          background: #fff
        }
        &::after{
          transform: rotate(90deg)
          left: 50%
          top: 50%
          background: #fff
        }
      }
    }
  }

  .e15{
    background: #228
    a {
      height: 45px
      line-height 45px
      padding: 0 20px
      &::before, &::after{
        position: absolute
        width: 45px
        height: 4px
        background: #FFF;
        content: ""
        opacity: 0.2
        transition: all 0.2s
      }
      &::before{
        top: 0
        left: 0
        transform: rotate(90deg)
        transform-origin: 0 0
      }
      &::after{
        right: 0
        bottom: 0
        transform: rotate(90deg)
        transform-origin: 100% 0
      }
      &:hover{
        &::before, &::after{
          opacity: 1
        }
        &::before{
          left: 50%
          transform: rotate(0deg) translateX(-50%)
        }
        &::after{
          right: 50%
          transform: rotate(0deg) translateX(50%)
        }
      }
    }
  }

  .e16{
    background: #068;
    a {
      padding: 10px;
      color: rgba(0,0,0,0.2)
      font-weight bold
      text-shadow: none
      &::before{
        content: "javascript"
        position: absolute;
        color: #fff
        transition: transform 0.3s, opacity 0.3s
      }
      &:hover{
        &::before{
          opacity: 0
          transform: scale(0.8)
        }
      }
    }
  }

  .e17{
    background: #068;
    a {
      padding: 10px;
      color: rgba(0,0,0,0.2)
      font-weight bold
      text-shadow: none
      &::before{
        content: "javascript"
        position: absolute;
        color: #fff
        opacity 0
        transform: rotate(45deg)
        // transform-origin: right bottom
        transition: transform 0.3s, opacity 0.3s
      }
      &:hover{
        &::before{
          opacity: 1
          transform: rotate(0deg)
        }
      }
    }
  }

  .e18{
    background: #d85;
    a {
      padding: 10px;
      color: #fff
      font-weight bold
      text-shadow: none
      &::before{
        content: "javascript"
        position: absolute;
        color: rgba(25,135,15,1)
        border-bottom: 2px solid #fff
        opacity 0
        padding: 10px
        top: 0
        left: 0
        transform: translateY(10px)
        // transform-origin: right bottom
        transition: transform 0.3s, opacity 0.3s
      }
      &:hover{
        &::before{
          opacity: 1
          transform: translateY(0)
        }
      }
    }
  }

  .e19{
    background: #f19f0f;
    a {
      padding: 10px 0
      color: #b4770d
      transition: color 0.5s
      &::before, &::after{
        position: absolute
        width: 100%
        height: 2px
        background: #b4770d;
        content: ""
        opacity: 0.5
        top: 50%
        left: 0
        transition: transform 0.3s, opacity 0.3s
      }
      &::before{
        top 0
      }
      &::after{
        top 100%
      }
      &:hover{
        color #fff
        &::before, &::after{
          opacity: 0.2
          top 50%
        }
        &::before{
          transform: rotate(45deg)
        }
        &::after{
          transform: rotate(-45deg)
        }
      }
    }
  }

  .e20{
    background: #685
    a {
      margin: 15px
      line-height 2em
      perspective 1000px
      width: 200px
      span{
        position relative
        display: inline-block
        padding: 0 15px
        background: #e35041;
        transition: transform 0.3s, background 0.3s
        transform-style: preserve-3d
        transform-origin: 50% 50% -100px;
        &::before{
          position: absolute
          top 0
          left: 100%
          width: 100%
          height: 100%
          background: #b53a2d;
          content: 'javascript'
          transform: rotateY(90deg)
          transform-origin: 0 50%
          transition: background 0.3s
        }
      }
      &:hover{
        span{
          background: #b53a2d;
          transform: rotateY(-90deg)
          &::before{
            background: #ef5e50
          }
        }
      }
    }
  }

  .e21{
    background: #d85;
    a {
      padding: 10px;
      border-top: 2px solid #357
      color: #fff
      font-weight bold
      text-shadow: none
      background: #999
      transition: background 0.3s, border 0.3s
      perspective 100px
      transform-style: preserve-3d
      &::before{
        content: "javascript"
        position: absolute;
        color: orange
        background: #fff
        padding: 10px
        top: 0
        left: 0
        transform: rotateX(270deg)
        transform-origin: top center
        transition: transform 0.6s
      }
      &:hover{
        background: #222
        border-color: orange
        &::before{
          transform: rotateX(2deg)
        }
      }
    }
  }

</style>