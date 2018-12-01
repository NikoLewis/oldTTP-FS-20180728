# stock_portfolio_app

web  based  stock  portfolio  app, for the  purpose  of  this  exercise  a  stock  is  simply  an  asset  that  can  be  bought  or  sold(like  a  house)  at  a  price  that  continuously  rises  and  falls  throughout  the  day.  Up  todate  pricing  information  willbe provided IEX  API.  A  guide  to  the  UI  can  beobserved  below.  Your  implementation  doesn’t  need  to  be  an  exact  match  but  shouldimplement  all  of  the  listed  user  stories.  In  addition  to  the  user  stories,  yoursubmission  will  be  assessed  for  readability,  code  organization,  commit  historyclarity,  overall  UI/UX,    and  overall  API  design.

##Heroku Deployment


##How to Run App Locally


##Technologies Used
JavaScript
React.js
React Router
Psql
Axios
Express
Flexbox

## Wire Frame:


## User Stories:

*1.*  As  a  user  I  want  to  create  a  new  account  with  my  name,  email,  and  password  sothat  I  can  buy  and  trade  stocks.Default  the  user’s  cash  account  balance  to  $5000.00  USD.A  user  can  only  register  once  with  any  given  email.

*2.*  As  a  user  I  want  to  authenticate  via  email  and  password  so  that  I  can  access  myaccount.

*3.*  As  a  user  I  want  to  buy  shares  of  stock  at  its  current  price  by  specifying  itsticker  symbol  and  number  of  shares  so  that  I  can  invest.A  user  can  only  buy  whole  number  quantities  of  shares.A  user  can  only  buy  shares  if  they  have  enough  cash  in  their  account  for  agiven  purchase.A  user  can  only  buy  shares  if  the  ticker  symbol  is  valid.

*4.*  As  a  user  I  want  to  view  a  list  of  all  transactions  I’ve  made  to  date(trades)  so  thatI  can  perform  an  audit.

*5.*  As  a  user  I  want  to  view  a  list  of  all  the  stocks  I  own  along  with  their  currentvalues  so  that  I  can  review  performance.Current  values  should  be  based  on  the  latest  price  and  quantity  owned  for  agiven  stock.

*6.*  As  a  user  I’d  like  to  see  the  font  color  of  stock  symbols  and  current  prices  in  myportfolio  change  dynamically  to  indicate  performance.Display  red  when  the  current  price  is  less  than  the  day’s  open  price.Display  grey  when  the  current  price  is  equal  to  the  day’s  open  price.Display  green  when  the  current  price  is  greater  than  the  day’s  open  price.
