<template>
    
    <div id="section-home" class="section-main">

        <div class="holder">

            <p>یکی از مشکلاتی که در انجمن‌ها یا گروه‌های پرسش و پاسخ با اون مواجه هستیم، پرسیدن سوال ناقص یا نامناسب هست که در نهایت به جواب اصولی هم ختم نمیشه و تنها اثر اون تلف شدن وقت پرسشگر و پاسخگو هست، از اونجایی که پرسیدن سوال صحیح نصف مسیر رسیدن به جواب صحیح رو تشکیل میده، سعی کنیم با پرسیدن سوال مناسب سریع‌تر به جواب برسیم و اتلاف وقت خودمون و دیگران رو به حداقل برسونیم</p>

            <section class="scenario scenario-wrong">

                <h2><i class="icon-x"></i>چیزی که شما می‌پرسید</h2>

                <hr>

                <SpeechBubble alignment="right" author="سناریو اول">
                    <template #content>ببخشید، کسی اینجا متخصص جاوا هست؟</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو دوم">
                    <template #content>کی اینجا گسسته بلده؟</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو سوم">
                    <template #content>چرا کدی که نوشتم کار نمی‌کنه؟</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو چهارم">
                    <template #content>می‌تونم یک سوال برنامه‌نویسی بپرسم؟</template>
                </SpeechBubble>

            </section>

            <p>در چنین نوع پرسش هایی به دلایل زیادی، <b>افرادی که دانش کافی برای راهنمایی دارند هم برای پاسخگویی مشارکت نمی‌کنند</b>، چون شما دارید چیزی می‌خواهید که بیشتر از اون چیزی هست که فکر می‌کنید</p>

            <section class="scenario scenario-wrong">

                <h2><i class="icon-x"></i>چیزی که شما می‌خواهید</h2>

                <hr>

                <SpeechBubble alignment="right" author="سناریو اول">
                    <template #content>ببخشید کسی اینجا متخصص جاوا هست که تمایل داشته باشه توی دونستن و تلاش برای رفع مشکل یا سوال من مشارکت کنه؟ هر اتفاقی هم که می‌خواد بیوفته مهم نیست و شاید هم حتی سوال من واقعا مرتبط با جاوا نباشه ولی خب از اونجایی که خودم تشخیص دادم که به جاوا ربط داره باید دنبال یک جاوا کار کاملا متخصص بگردم که بیاد به‌صورت رایگان وقت بزاره و سوال من رو جواب بده، بازم تاکید می‌کنم که طرف باید متخصص جاوا باشه و اگه متخصص نباشه و با این حال جواب سوال من رو بلد باشه من نمی‌خوام که جواب بده و دقیقا باید متخصص باشه</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو دوم">
                    <template #content>کی اینجا هست که گسسته بلد باشه و بیکار و الاف باشه تا بیاد و به پیام من پاسخ بده و بگه که : آره آقا من گسسته بلدم و می‌خوام تورو راهنمایی کنم هر سوالی داری بپرس، هرگونه سوالی از گسسته داشته باشی من می‌تونم جواب بدم چون که من خدای رشته گسسته هستم و مطمئنا هرگونه سوالی در این زمینه داشته باشی من می‌تونم جواب بدم بدون اینکه اصلا بدونم سوالت چی هست</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو سوم">
                    <template #content>من یک کدی نوشتم و در خیالم انتظار دارم که فلان کار رو انجام بده، برای همین کد ناقص خودم رو برای شما می‌فرستم و انتظار دارم که بدون اینکه بدونید که من انتظار دارم که کد من چیکار کنه، شما حدس بزنید و مشکلش رو برای من پیدا کنید و بگید</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو چهارم">
                    <template #content>من در دریا هستم و وسط دریا داد می‌زنم و می‌پرسم که آیا می‌تونم شنا کنم یا نه</template>
                </SpeechBubble>

            </section>

            <p>در سوالات بالا یا موارد مشابه، شما دارید روی دوش بقیه مسئولیت قرار می‌دهید و اعتماد به‌نفس و توانایی‌های بقیه رو زیر سوال می‌برید و دایره افرادی که می‌تونند به سوال شما پاسخ بدهند رو کوچک‌تر می‌کنید، شما بدون اینکه سوال واقعی خودتون رو بپرسید، دارید مقدمه‌چینی می‌کنید تا ببینید که اصلا می‌ارزه که سوالتون رو بپرسید یا نه<br><br>بخش آزاردهنده ماجرا اینجاست که <b>وقتی شما خودتون به‌قدری حوصله ندارید که برای توضیح مشکل یا سوالتون وقت بگذارید، چرا انتظار دارید یکی برای کمک به شما حوصله کنه و به‌صورت رایگان وقت بگذاره؟</b> در چنین شرایطی می‌تونید به‌دنبال یک منتور باشید تا در ازای پرداخت هزینه بهتون دائما راهنمایی ارائه کنه</p>

            <section class="scenario scenario-correct">

                <h2><i class="icon-check"></i>چیزی که شما باید بپرسید</h2>

                <hr>

                <SpeechBubble alignment="right" author="سناریو اول">
                    <template #content>سلام، من می‌خواهم در زبان جاوا فلان کار را انجام دهم، برای انجام اینکار باید چه مواردی رو یاد بگیرم و مطالعه کنم؟</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو دوم">
                    <template #content>سلام، من در درس گسسته مقطع فلان و رشته بهمان، در بخش فلان مشکل بهمان را دارم،‌ کسی می‌تونه راهنمایی کنه که چطور می‌تونم حل کنم؟</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو سوم">
                    <template #content>سلام، من می‌خواهم فلان کار را در پلتفرم بهمان و زبان فلان انجام دهم، این کدی هست که من نوشته‌ام و این خروجی هست که من می‌گیرم، می‌خواهم خروجی فلان را بگیرم، کدم را باید به چه صورتی تغییر بدهم تا نتیجه فوق برسم؟</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو چهارم">
                    <template #content>سلام، من در حوزه فلان برنامه‌نویسی مشکل بهمان را دارم، آیا کسی می‌تونه راهنمایی کنه تا مشکلم رو حل کنم؟</template>
                </SpeechBubble>

                <hr>

                <SpeechBubble alignment="right" author="سناریو کلی">
                    <template #content>سلام وقت‌بخیر، یک سوال درمورد فلان داشتم<br>مشکلی که دارم فلان هست<br>فلان کارها رو انجام دادم<br>فلان نتیجه رو گرفتم<br>می‌خواهم فلان نتیجه رو بگیرم<br>ممنون میشم اگر کسی وقت داشت راهنمایی کنه</template>
                </SpeechBubble>

            </section>

            <p>لطفا این رو هم مد نظر داشته باشید که قبل از پرسیدن سوال، حتما توی گوگل به‌دنبال مشکلتون بگردید چون به احتمال خیلی زیاد قبل از شما هم افرادی به این مشکل برخورد کردند و در سایت های مختلف مطرح کرده‌اند و جواب گرفته‌اند<br><br>همچنین این مورد رو هم به‌یاد داشته باشید که معمولا کسی برای پاسخگویی به سوالات شما هزینه‌ای دریافت نمی‌کنه، پس مجبور به پاسخگویی به سوالات شما نیست و بلکه داره از با ارزش‌ترین سرمایه زندگی‌اش که زمان هست، برای شما مایه می‌گذاره، پس تشکر یادتون نره (:</p>

        </div>

    </div>

</template>

<script>
import SpeechBubble from '../components/SpeechBubble.vue'

export default {
    name: 'HomeView',
    components: {
        SpeechBubble,
    },
    mounted() {
        
        window.scrollTo({top: 0, behavior: 'smooth'});

    }
}
</script>
