*,
::before,
::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    background: black;
    font-family: Arial, Helvetica, sans-serif;
}

.cube {
    margin: 200px auto 0;
    width: 100px;
    height: 100Px;
    position: relative;
    transform-style: preserve-3d;
    transform: rotateX(-36deg) rotateY(-45deg);
    animation: spin 3s infinite cubic-bezier(0.16, 0.61, 0.49, 0.91);

}

@keyframes spin {
    33% {
        transform: rotateX(-36deg) rotateY(-405deg);
    }

    100% {
        transform: rotateX(-36deg) rotateY(-405deg);
    }

}


.face {
    position: absolute;
    width: 100%;
    height: 100%;
    background: rgb(12, 12, 12);
    border: 2px solid #fff;
    border-radius: 5px;
    box-shadow: 0 0 15px #fff;
}

.top {
    transform: rotateX(90deg) translateZ(50px);
    animation: shift-top 3s infinite ease-out;
}

.bottom {
    transform: rotateX(-90deg) translateZ(50px);
    animation: shift-bottom 3s infinite ease-out;
}

.right {
    transform: rotateY(90deg) translateZ(50px);
    animation: shift-right 3s infinite ease-out;
}

.left {
    transform: rotateY(-90deg) translateZ(50px);
    animation: shift-left 3s infinite ease-out;
}

.front {
    transform: translateZ(50px);
    animation: shift-front 3s infinite ease-out;
}

.back {
    transform: rotateY(-180deg) translateZ(50px);
    animation: shift-back 3s infinite ease-out;
}

@keyframes shift-top {
    33% {
        transform: rotateX(90deg) translateZ(50px);
    }

    50% {
        transform: rotateX(90deg) translateZ(100px);
    }

    60% {
        transform: rotateX(90deg) translateZ(100px);
    }

    75% {
        transform: rotateX(90deg) translateZ(50px);
    }
}

@keyframes shift-bottom {
    33% {
        transform: rotateX(-90deg) translateZ(50px);
    }

    50% {
        transform: rotateX(-90deg) translateZ(100px);
    }

    60% {
        transform: rotateX(-90deg) translateZ(100px);
    }

    75% {
        transform: rotateX(-90deg) translateZ(50px);
    }
}

@keyframes shift-right {
    33% {
        transform: rotateY(90deg) translateZ(50px);
    }

    50% {
        transform: rotateY(90deg) translateZ(100px);
    }

    60% {
        transform: rotateY(90deg) translateZ(100px);
    }

    75% {
        transform: rotateY(90deg) translateZ(50px);
    }
}

@keyframes shift-left {
    33% {
        transform: rotateY(-90deg) translateZ(50px);
    }

    50% {
        transform: rotateY(-90deg) translateZ(100px);
    }

    60% {
        transform: rotateY(-90deg) translateZ(100px);
    }

    75% {
        transform: rotateY(-90deg) translateZ(50px);
    }
}

@keyframes shift-front {
    33% {
        transform: translateZ(50px);
    }

    50% {
        transform: translateZ(100px);
    }

    60% {
        transform: translateZ(100px);
    }

    75% {
        transform: translateZ(50px);
    }
}

@keyframes shift-back {
    33% {
        transform: rotateY(-180deg) translateZ(50px);
    }

    50% {
        transform: rotateY(-180deg) translateZ(100px);
    }

    60% {
        transform: rotateY(-180deg) translateZ(100px);
    }

    75% {
        transform: rotateY(-180deg) translateZ(50px);
    }
}
