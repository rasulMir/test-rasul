<template>
    <div class="main">
        <div class="main-document bg-white">
            <div class="doc-header">
                <h1 class="doc-title text-center text-subtitle1 text-weight-bold">
                    Договор предоплаты купли-продажи набора кухонной мебели
                </h1>
                <div class="doc-header-body">
                    <div class="doc-header-date">
                        <div class="doc-header-date-city">
                            г. Алматы
                        </div>
                        <div class="doc-header-date-day underline">{{ day }}</div>
                        <div class="doc-header-date-month underline">{{ month }}</div>
                        <div class="doc-header-date-year">2023 г.</div>
                    </div>
                    <div class="doc-header-sign">&lt;&lt; <span class="underline">{{ sign }}</span> &gt;&gt;</div>
                </div>
                <div class="doc-header-content">
                    <p class="doc-descr">
                        <span class="text-bold first-line">ТОО «Test»</span> в лице директора Иванов Иван, действующего на
                        основании Устава, именуемое в дальнейшем «Продавец», с одной стороны, и гр. <span
                            class="doc-fullname underline">{{ fullname }}</span> уд.личности: № <span
                            class="doc-id-number underline">{{ idNumber }}</span>, выданный <span
                            class="doc-id-date underline">{{ idDate }}</span>, проживающий по адресу: <span
                            class="doc-address underline">{{ address }}</span>, именуемый в дальнейшем «Покупатель», с
                        другой стороны, заключили настоящий Договор предоплаты о нижеследующем:

                    </p>
                </div>
            </div>
            <ul class="doc-body">
                <li class="doc-item">
                    <h2 class="doc-title text-body1 text-weight-bold">1.ПРЕДМЕТ ДОГОВОРА.</h2>
                    <p class="doc-descr">
                        <span class="first-line">1.1.</span>
                        Продавец обязуется передать в собственность Покупателя набор мебели для кухни (далее «Товар»), а
                        Покупатель обязуется принять Товар и уплатить Продавцу за него денежную сумму, в порядке и размере,
                        предусмотренных Договором.
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">1.2.</span>
                        Предметом Договора является Товар, заказанный Покупателем и соответствующий описанию,
                        предусмотренного Приложением №1 к Основному Договору;
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">1.3.</span>
                        Покупателю могут быть предоставлены дополнительные услуги по замеру помещения, установке (монтажу) и
                        доставке Товара:
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">1.3.1.</span>
                        стоимость Услуг не включается в стоимость Товара. Указанные услуги предоставляются Покупателю только
                        при условии приобретения Товара.
                    </p>
                </li>

                <li class="doc-item">
                    <h2 class="doc-title text-body1 text-weight-bold">2. ПОРЯДОК ИСПОЛНЕНИЯ ДОГОВОРА</h2>
                    <p class="doc-descr">
                        <span class="first-line">2.1.</span>
                        Покупатель, ознакомившись с демонстрируемыми образцами, потребительскими свойствами и условиями
                        поставки, заказывает необходимый ему Товар и заключает Договор предоплаты. При этом, стороны в
                        дальнейшем обязуются заключить Основной Договор купли-продажи кухонного набора (далее «Основной
                        Договор»).
                    </p>
                </li>

                <li class="doc-item">
                    <h2 class="doc-title text-body1 text-weight-bold">3. ПОРЯДОК РАСЧЕТОВ И СУММА ДОГОВОРА</h2>
                    <p class="doc-descr">
                        <span class="first-line">3.1.</span>
                        Цена Товара и дополнительных услуг определяется в момент заключения Основного Договора:
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">3.1.1.</span>
                        в момент заключения Договора предоплаты Покупатель вносит предоплату на счет Продавца в размере
                        <span class="underine doc-price">{{ price }}</span> тенге;
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">3.1.2.</span>
                        оставшуюся сумму Покупатель оплачивает в момент заключения Основного Договора
                    </p>
                </li>

                <li class="doc-item">
                    <h2 class="doc-title text-body1 text-weight-bold">4. СРОК ДЕЙСТВИЯ ДОГОВОРА</h2>
                    <p class="doc-descr">
                        <span class="first-line">4.1.</span>
                        Договор вступает в силу с момента его подписания.
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">4.2.</span>
                        Датой окончания договора будет дата передачи Покупателю или лицам, его представляющим, Товара,
                        соответствующего описанию, указанному в Приложениях Основного Договора. При оказании услуг,
                        указанных в Договоре, Договор считается исполненным с момента выполнения этих услуг.
                    </p>
                </li>

                <li class="doc-item">
                    <h2 class="doc-title text-body1 text-weight-bold">5. ОТВЕТСТВЕННОСТЬ СТОРОН</h2>
                    <p class="doc-descr">
                        <span class="first-line">5.1. </span>
                        Право собственности на Товар переходит к Покупателю в момент 100% оплаты стоимости Товара.
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">5.2.</span>
                        В случае отказа Покупателем от Товара, после его письменного обращения, Продавец, в течение 14
                        (четырнадцати) рабочих дней, возвращает сумму, оплаченную Покупателем за Товар, за вычетом
                        фактически понесенных Продавцом расходов.
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">5.3.</span>
                        Стороны освобождаются от ответственности за частичное или полное неисполнение обязательств по
                        настоящему договору, если это неисполнение явилось следствием обстоятельств непреодолимой силы,
                        возникших после заключения настоящего договора в результате событий чрезвычайного характера, которые
                        сторона не могла предвидеть или предотвратить разумными мерами (форс-мажорные обстоятельства). К
                        таким событиям относятся наводнения, пожар, землетрясения, взрыв, шторм, оседание почвы, эпидемия и
                        иные явления природы, военные действия, технологические катастрофы.
                    </p>
                </li>

                <li class="doc-item">
                    <h2 class="doc-title text-body1 text-weight-bold">6. РАЗРЕШЕНИЕ СПОРОВ</h2>
                    <p class="doc-descr">
                        <span class="first-line">6.1. </span>
                        Все разногласия и споры, которые могут возникнуть между сторонами из настоящего договора и в связи с
                        ним, будут по возможности решаться путем переговоров.
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">6.2.</span>
                        6.2. В случае, когда возникшие споры путем переговоров не урегулированы, они подлежат разрешению в
                        судах по месту нахождения Продавца.
                    </p>
                </li>

                <li class="doc-item">
                    <h2 class="doc-title text-body1 text-weight-bold">7. ФОРС-МАЖОРНЫЕ ОБСТОЯТЕЛЬСТВА</h2>
                    <p class="doc-descr">
                        <span class="first-line">7.1. </span>
                        В случае наступления форс-мажорных обстоятельств пострадавшая Сторона обязана в кратчайшие сроки
                        предупредить другую Сторону о невозможности исполнения своих обязательств по настоящему Договору.
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">7.2.</span>
                        При этом ни одна Сторона не может требовать возмещения каких-либо убытков или потерь, связанных с
                        невыполнением Договора.
                    </p>
                </li>

                <li class="doc-item">
                    <h2 class="doc-title text-body1 text-weight-bold">8. ПРОЧИЕ УСЛОВИЯ ДОГОВОРА</h2>
                    <p class="doc-descr">
                        <span class="first-line">8.1. </span>
                        Настоящий Договор, а также любые приложения к нему, заключается между двумя Сторонами в двух
                        экземплярах, имеющих равную юридическую силу, и передаются по одному экземпляру каждой из сторон.
                    </p>
                    <p class="doc-descr">
                        <span class="first-line">8.2.</span>
                        Ни одна из сторон договора не вправе передавать свои права по Договору другому лицу без письменного
                        согласия другой Стороны
                    </p>
                </li>

            </ul>
            <div class="doc-footer">
                <h2 class="doc-title text-body1 text-weight-bold">АДРЕСА И РЕКВИЗИТЫ СТОРОН.</h2>
                <div class="doc-footer-table">

                    <div class="row">

                        <div class="col-6 table-item ">
                            <div class="doc-table-title text-center text-weight-bold">
                                ПРОДАВЕЦ:
                            </div>
                            <div class="table-item-txt">
                                ТОО «Test»
                            </div>
                        </div>
                        <div class="col-6 table-item ">
                            <div class="doc-table-title text-center text-weight-bold">
                                ПОКУПАТЕЛЬ:
                            </div>
                            <div class="table-item-txt">
                                наименование ФИО
                            </div>
                        </div>

                    </div>
                    <div class="row">
                        <div class="table-item col-6">
                            <div class="table-item-txt">
                                Юр. адрес: г. Алматы, ул. Дундича д. 245
                            </div>
                        </div>
                        <div class="table-item col-6">
                            <div class="table-item-txt">
                                Регистрация:
                            </div>
                            <div class="table-item-txt">
                                Место жительство:
                            </div>
                            <div class="table-item-txt">
                                Телефон
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="table-item col-6">
                            <div class="table-item-txt">
                                Почтовый адрес:00000
                            </div>
                        </div>

                        <div class="table-item col-6">
                            <div class="table-item-txt">
                                Почтовый адрес:
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="table-item col-6">
                            <div class="table-item-txt">
                                БИН: 1111111111
                            </div>
                        </div>

                        <div class="table-item col-6">
                            <div class="table-item-txt">
                                ИИН
                            </div>
                        </div>
                    </div>
                    <div class="row">

                        <div class="table-item col-6">
                            <div class="table-item-txt">
                                АО «KaspiBank»
                            </div>
                            <div class="table-item-txt">
                                p/c: 11111111111
                            </div>
                            <div class="table-item-txt">
                                БИК: CASPKZKA
                            </div>
                        </div>

                        <div class="table-item col-6">
                            <div class="table-item-txt">
                                Удост. личности №:
                            </div>
                            <div class="table-item-txt">
                                Выдано когда: <span class="underline">{{ date }}</span> . Кем: <span class="underline">{{ director }}</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="main-fields">
            <q-input outlined margin v-model="sign" label="Подпись" />
            <q-input outlined v-model="day" label="День" />
            <q-input outlined v-model="month" label="Месяц" />
            <q-input outlined v-model="fullname" label="Полное имя" />
            <q-input outlined v-model="idNumber" label="Номер уд.личности" />
            <q-input outlined v-model="idDate" label="Дата выдачи уд.личности" />
            <q-input outlined v-model="address" label="Адрес" />
            <q-input outlined v-model="price" label="Предоплата" />
            <q-input outlined v-model="director" label="Выдано кем" />
            <q-input outlined v-model="date" label="Выдано когда" />
        </div>
    </div>
</template>
<style>
@import '../css/doc.scss';
</style>
<script>
export default {
    data() {
        return {
            sign: '  ',
            day: '  ',
            month: '  ',
            fullname: '  ',
            idNumber: '  ',
            idDate: '  ',
            address: '  ',
            date: '  ',
            director: '  ',
            price: '  ',
        }
    },

}
</script>