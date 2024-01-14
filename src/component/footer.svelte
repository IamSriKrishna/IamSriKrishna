<script>
    let recipient = 'srik9585a@gmail.com';
    let subject = 'Subject of the email';
    let body = 'Body of the email';
</script>
<footer
    class="py-20 sm:py-32 bg-black border-t border-solid border-violet-950 flex flex-col gap-4 sm:gap-8 justify-center items-center"
>
    <p class="px-4 py-2 bg-white text-slate-950 font-medium">
        Connect with me &darr;
    </p>
    <div class="flex flex-col gap-4 items-center justify-center">
        <p>
            <b class="pr-2">Email</b>
            <a href={`https://mail.google.com/mail/?view=cm&fs=1&to=${encodeURIComponent(recipient)}&su=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`} target="_blank" class="text-violet-400"
                >IamSriKrishna<sup class=""
                    ><span class="text-xs scale-75 pl-0.5"
                        ><i
                            class="fa-solid fa-arrow-up-right-from-square text-xs scale-[75%]"
                        /></span
                    ></sup
                ></a
            >
        </p>
        <p>
            <b class="pr-2">GitHub</b>
            <a href="https://github.com/IamSriKrishna" target="_blank" class="text-violet-400"
                >IamSriKrishna<sup class=""
                    ><span class="text-xs scale-75 pl-0.5"
                        ><i
                            class="fa-solid fa-arrow-up-right-from-square text-xs scale-[75%]"
                        /></span
                    ></sup
                ></a
            >
        </p>
        <p>
            <b class="pr-2">LinkedIn</b>
            <a href="https://www.linkedin.com/in/sri-krishna-m/" target="_blank" class="text-violet-400"
                >IamSriKrishna<sup class=""
                    ><span class="text-xs scale-75 pl-0.5"
                        ><i
                            class="fa-solid fa-arrow-up-right-from-square text-xs scale-[75%]"
                        /></span
                    ></sup
                ></a
            >
        </p>
    </div>
</footer>

