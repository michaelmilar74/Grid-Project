# Grid-Project

.container {
  display: grid;
  height:100vh;
  grid-template-columns: 0.21fr 1.51fr 1.21fr 0.81fr;
  grid-template-rows:  0.21fr, 1.5fr,1.2fr,0.8fr;
  grid-template-areas:
    "nav nav nav nav"
    "sidebar header header header"
    "sidebar content1 content2 content3"
    "sidebar footer footer footer";
  gap: 0.2rem;
  font-family: "Inter", sans-serif;
  font-weight: 800;
  text-transform: uppercase;
  background-color: lightblue;
  padding: 20px;
  text-align: right;
}

.nav { grid-area: nav; }
.sidebar { grid-area: navar; }
.header { grid-area: header; }
.content1 { grid-area: content1; }
.content2 { grid-area: content2; }
.content3 { grid-area: content3; }
.footer { grid-area: footer; }


.item1 { grid-area: header; }
.item2 { grid-area: navbar; }
.item3 { grid-area: content1; }
.item4 { grid-area: content1; }
.item5 { grid-area: footer; }

.grid-container {
  display: grid;
  grid-template-areas:
    'header header header header header header'
    'navbar,navbar,navbar'
    'content1 content2 content 3 right right'
    'menu footer footer footer footer footer';
  gap: 10px;
  background-color: #2196F3;
  padding: 10px;
}

.grid-container > div {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}
