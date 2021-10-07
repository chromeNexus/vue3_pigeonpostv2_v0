<template>
  <div class="bg-white">
    <!-- Background color split screen for large screens -->
    <div
      class="hidden lg:block fixed top-0 left-0 w-1/2 h-full bg-white"
      aria-hidden="true"
    />
    <div
      class="hidden lg:block fixed top-0 right-0 w-1/2 h-full bg-gray-50"
      aria-hidden="true"
    />

    <div
      class="
        relative
        grid grid-cols-1
        gap-x-16
        max-w-7xl
        mx-auto
        lg:px-8 lg:grid-cols-2
        xl:gap-x-48
      "
    >
      <h1 class="sr-only">Order information</h1>

      <Form
        class="
          pt-16
          pb-36
          px-4
          sm:px-6
          lg:pb-16 lg:px-0 lg:row-start-1 lg:col-start-1
        "
      >
        <div class="max-w-lg mx-auto lg:max-w-none">
          <section aria-labelledby="contact-info-heading">
            <h2
              id="contact-info-heading"
              class="text-lg font-medium text-gray-900"
            >
              Contact information
            </h2>

            <div class="mt-6">
              <label
                for="email-address"
                class="block text-sm font-medium text-gray-700"
                >Email address</label
              >
              <div class="mt-1">
                <input
                  type="email"
                  id="email-address"
                  name="email-address"
                  autocomplete="email"
                  class="
                    block
                    w-full
                    border-gray-300
                    rounded-md
                    shadow-sm
                    focus:ring-indigo-500 focus:border-indigo-500
                    sm:text-sm
                  "
                />
              </div>
            </div>
          </section>

          <section aria-labelledby="shipping-heading" class="mt-10">
            <div class="mt-6 grid grid-cols-1 gap-y-6 gap-x-4 sm:grid-cols-3">
              <div class="col-span-3 sm:col-span-4">
                <label
                  for="name-on-card"
                  class="block text-sm font-medium text-gray-700"
                  >Name</label
                >
                <div class="mt-1">
                  <input
                    type="text"
                    id="name-on-card"
                    name="name-on-card"
                    autocomplete="cc-name"
                    class="
                      block
                      w-full
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:ring-indigo-500 focus:border-indigo-500
                      sm:text-sm
                    "
                  />
                </div>
              </div>

              <div class="sm:col-span-3">
                <label
                  for="company"
                  class="block text-sm font-medium text-gray-700"
                  >Company</label
                >
                <div class="mt-1">
                  <input
                    type="text"
                    id="company"
                    name="company"
                    class="
                      block
                      w-full
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:ring-indigo-500 focus:border-indigo-500
                      sm:text-sm
                    "
                  />
                </div>
              </div>

              <div class="sm:col-span-3">
                <label
                  for="address"
                  class="block text-sm font-medium text-gray-700"
                  >Address</label
                >
                <div class="mt-1">
                  <input
                    type="text"
                    id="address"
                    name="address"
                    autocomplete="street-address"
                    class="
                      block
                      w-full
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:ring-indigo-500 focus:border-indigo-500
                      sm:text-sm
                    "
                  />
                </div>
              </div>

              <div class="sm:col-span-3">
                <label
                  for="apartment"
                  class="block text-sm font-medium text-gray-700"
                  >Apartment, suite, etc.</label
                >
                <div class="mt-1">
                  <input
                    type="text"
                    id="apartment"
                    name="apartment"
                    class="
                      block
                      w-full
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:ring-indigo-500 focus:border-indigo-500
                      sm:text-sm
                    "
                  />
                </div>
              </div>

              <div>
                <label
                  for="city"
                  class="block text-sm font-medium text-gray-700"
                  >City</label
                >
                <div class="mt-1">
                  <input
                    type="text"
                    id="city"
                    name="city"
                    class="
                      block
                      w-full
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:ring-indigo-500 focus:border-indigo-500
                      sm:text-sm
                    "
                  />
                </div>
              </div>
              <div>
                <label
                  for="province"
                  class="block text-sm font-medium text-gray-700"
                  >Province</label
                >
                <div class="mt-1">
                  <input
                    type="text"
                    id="province"
                    name="province"
                    class="
                      block
                      w-full
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:ring-indigo-500 focus:border-indigo-500
                      sm:text-sm
                    "
                  />
                </div>
              </div>
              <div>
                <label
                  for="postal-code"
                  class="block text-sm font-medium text-gray-700"
                  >Postal code</label
                >
                <div class="mt-1">
                  <input
                    type="text"
                    id="postal-code"
                    name="postal-code"
                    autocomplete="postal-code"
                    class="
                      block
                      w-full
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:ring-indigo-500 focus:border-indigo-500
                      sm:text-sm
                    "
                  />
                </div>
              </div>
            </div>
            <div class="mt-6">
              <label
                for="email-address"
                class="block text-sm font-medium text-gray-700"
                >Email address</label
              >
              <div class="mt-1">
                <input
                  type="email"
                  id="email-address"
                  name="email-address"
                  autocomplete="email"
                  class="
                    block
                    w-full
                    border-gray-300
                    rounded-md
                    shadow-sm
                    focus:ring-indigo-500 focus:border-indigo-500
                    sm:text-sm
                  "
                />
              </div>
            </div>
          </section>

          <section aria-labelledby="billing-heading" class="mt-10">
            <h2 id="billing-heading" class="text-lg font-medium text-gray-900">
              Billing information
            </h2>

            <div class="mt-6 flex items-center">
              <input
                id="same-as-shipping"
                name="same-as-shipping"
                type="checkbox"
                checked=""
                class="
                  h-4
                  w-4
                  border-gray-300
                  rounded
                  text-indigo-600
                  focus:ring-indigo-500
                "
              />
              <div class="ml-2">
                <label
                  for="same-as-shipping"
                  class="text-sm font-medium text-gray-900"
                  >Same as shipping information</label
                >
              </div>
            </div>
          </section>

          <div
            class="
              mt-10
              pt-6
              border-t border-gray-200
              sm:flex sm:items-center sm:justify-between
            "
          >
            <button
              type="submit"
              class="
                w-full
                bg-indigo-600
                border border-transparent
                rounded-md
                shadow-sm
                py-2
                px-4
                text-sm
                font-medium
                text-white
                hover:bg-indigo-700
                focus:outline-none
                focus:ring-2
                focus:ring-offset-2
                focus:ring-offset-gray-50
                focus:ring-indigo-500
                sm:ml-6 sm:order-last sm:w-auto
              "
            >
              Continue
            </button>
            <p
              class="
                mt-4
                text-center text-sm text-gray-500
                sm:mt-0 sm:text-left
              "
            >
              You won't be charged until the next step.
            </p>
          </div>
        </div>
      </Form>
    </div>
  </div>
</template>

<script>
/* import {
  Popover,
  PopoverButton,
  PopoverOverlay,
  PopoverPanel,
  TransitionChild,
  TransitionRoot,
} from "@headlessui/vue"; */
/* import { ChevronUpIcon } from "@heroicons/vue/solid"; */
import { Field, Form, ErrorMessage, useField, useForm
 } from "vee-validate";
import { object, string, number, boolean } from 'yup'


const products = [
  {
    id: 1,
    name: "Micro Backpack",
    href: "#",
    price: "$70.00",
    color: "Moss",
    size: "5L",
    imageSrc:
      "https://tailwindui.com/img/ecommerce-images/checkout-page-04-product-01.jpg",
    imageAlt:
      "Moss green canvas compact backpack with double top zipper, zipper front pouch, and matching carry handle and backpack straps.",
  },
  // More products...
];

export default {
  name: "TestForm",
  components: {
    Field,
    Form,
    ErrorMessage,

    /*   Popover,
    PopoverButton,
    PopoverOverlay,
    PopoverPanel,
    TransitionChild,
    TransitionRoot,
    ChevronUpIcon, */
  },
  setup() {
    return {
      products,
    };
  },
};
</script>
