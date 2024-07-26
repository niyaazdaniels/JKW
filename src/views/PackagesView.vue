<template>
  <section id="packages">
    <div class="packages-heading p-4">
      <h2>Pricing & Packages</h2>
    </div>

    <div class="selection-options">
      <button class="button-option bg-transparent">@Your Home</button>
      <button class="button-option bg-transparent">@Your Office</button>
      <button class="button-option bg-transparent">@Your Dealership</button>
    </div>

    <div class="bronze-package mb- 5">
      <div class="container package-container">
        <div class="package-header">
          <h2>Package 1</h2>
        </div>
        <div class="row">
          <div class="col-md-4">
            <h4><strong>Bronze</strong></h4>
            <img
              src="../assets/2017_audi_r8-v10-plus-coupe_2017_audi_r8-v10-plus-coupe_c4ed2440-df88-4447-8b9d-64aefbe3f891-dAPAFL-33569-33570-scaled.webp"
              alt="Car Image"
              class="package-image img-fluid rounded shadow"
            />
          </div>
          <div class="col-md-4">
            <h4><strong>All-Inclusive:</strong></h4>
            <div class="package-details">
              <ul class="list-circle">
                <li>High level safe wash</li>
                <li>High pressure rinse</li>
                <li>Snow foam wash</li>
                <li>High pressure rinse</li>
                <li>Door jams, boot jams</li>
                <li>Pedals cleaned</li>
                <li>Air vents brushed clean</li>
                <li>Plastics cleaned and UV protected</li>
                <li>Deep clean brush out and vacuum</li>
                <li>New car smell</li>
                <li>Wheel arches cleaned and nourished</li>
                <li>Door rubbers cleaned and nourished</li>
              </ul>
            </div>
          </div>
          <div class="col-md-4 mt-3 pt-3">
            <div class="package-details">
              <ul class="list-circle">
                <li>Glass mirrors Crystal clear</li>
                <li>Grills bumpers mirrors dried out</li>
                <li>Bumpers, lips, defusers and tyres nourished</li>
                <li>Exhaust tips cleaned and polished</li>
                <li>Spray coating 6 month protection</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row mt-3 text-start">
          <div class="col-md-4 text-start package-pricing">
            <h4><strong>Pricing:</strong></h4>
            <ul class="list-unstyled text-start">
              <li>Small vehicle: R799</li>
              <li>Medium size vehicle: R999</li>
              <li>Large size vehicle: R1200</li>
            </ul>
            <p class="text text-start"><strong>Duration:</strong> 90 minutes</p>
            <button class="btn btn-dark get-started-btn">
              GET STARTED NOW
            </button>
          </div>
        </div>
      </div>
    </div>

    <div class="silver-package">
      <div class="container mt-5">
        <div class="package-container">
          <div class="package-header">
            <h2>Package 2</h2>
          </div>
          <div class="row">
            <div class="col-md-4">
              <h4><strong>Silver</strong></h4>
              <img
                src="../assets/jaguar.webp"
                alt="Car Image"
                class="package-image img-fluid rounded shadow"
              />
            </div>
            <div class="col-md-4">
              <h4><strong>All-Inclusive:</strong></h4>
              <div class="package-details">
                <ul class="list-circle">
                  <li>High level safe wash</li>
                  <li>High pressure rinse</li>
                  <li>Snow foam wash</li>
                  <li>High pressure rinse</li>
                  <li>Door jams, boot jams</li>
                  <li>Pedals cleaned</li>
                  <li>Air vents brushed clean</li>
                  <li>Plastics cleaned and UV protected</li>
                  <li>Deep clean brush out and vacuum</li>
                  <li>New car smell</li>
                  <li>Wheel arches cleaned and nourished</li>
                  <li>Door rubbers cleaned and nourished</li>
                </ul>
              </div>
            </div>
            <div class="col-md-4 mt-3 pt-3">
              <div class="package-details">
                <ul class="list-circle">
                  <li>Glass mirrors Crystal clear</li>
                  <li>Grills bumpers mirrors dried out</li>
                  <li>Bumpers, lips, defusers and tyres nourished</li>
                  <li>Exhaust tips cleaned and polished</li>
                  <li>Clay bar treatment</li>
                  <li>
                    Removes bonded contamination on the vehicle's windows and
                    paint surfaces
                  </li>
                  <li>
                    Glazing machine polish provides a wet glossy paint finish
                  </li>
                  <li>Spray coating 6 month protection</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="row mt-3 text-start">
            <div class="col-md-4 text-start package-pricing">
              <h4><strong>Pricing:</strong></h4>
              <ul class="list-unstyled text-start">
                <li>Small vehicle: R1799</li>
                <li>Medium size vehicle: R1999</li>
                <li>Large size vehicle: R2199</li>
              </ul>
              <p class="text text-start">
                <strong>Duration:</strong> 180 minutes
              </p>
              <button
                class="btn btn-dark get-started-btn"
                @click="startBooking"
              >
                GET STARTED NOW
              </button>
            </div>
            <div class="col-md-8 px-4 text-start">
              <h4><strong>Optional extras:</strong></h4>
              <ul class="list-unstyled text-start">
                <li>Nasiol 1 year ceramic: R1500</li>
                <li>Nasiol 3 year ceramic coating: R2500</li>
                <li>Nasiol 5 year ceramic coating: R4500</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="gold-package">
      <div class="container mt-5">
        <div class="package-container">
          <div class="package-header">
            <h2>Package 3</h2>
          </div>
          <div class="row">
            <div class="col-md-4">
              <h4><strong>Gold</strong></h4>
              <img
                src="../assets/range_rover_sport.jpg"
                alt="Car Image"
                class="package-image img-fluid rounded shadow"
              />
            </div>
            <div class="col-md-4">
              <h4><strong>All-Inclusive:</strong></h4>
              <div class="package-details">
                <ul class="list-circle">
                  <li>High level safe wash</li>
                  <li>High pressure rinse</li>
                  <li>Snow foam wash</li>
                  <li>High pressure rinse</li>
                  <li>Door jams, boot jams</li>
                  <li>Pedals cleaned</li>
                  <li>Air vents brushed clean</li>
                  <li>Plastics cleaned and UV protected</li>
                  <li>Deep clean brush out and vacuum</li>
                  <li>New car smell</li>
                  <li>Wheel arches cleaned and nourished</li>
                  <li>Door rubbers cleaned and nourished</li>
                </ul>
              </div>
            </div>
            <div class="col-md-4 mt-3 pt-3">
              <div class="package-details">
                <ul class="list-circle">
                  <li>Glass mirrors Crystal clear</li>
                  <li>Grills bumpers mirrors dried out</li>
                  <li>Bumpers, lips, defusers and tyres nourished</li>
                  <li>Exhaust tips cleaned and polished</li>
                  <li>Clay bar treatment</li>
                  <li>
                    Removes bonded contamination on the vehicle's windows and
                    paint surfaces
                  </li>
                  <li>
                    Stage 1 Paint correction 50% improvement on defected paint
                    Removes light swirls, holograms and blemishes
                  </li>
                  <li>Spray coating 6 month protection</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="row mt-3 text-start">
            <div class="col-md-4 text-start package-pricing">
              <h4><strong>Pricing:</strong></h4>
              <ul class="list-unstyled text-start">
                <li>Small vehicle: R2099</li>
                <li>Medium size vehicle: R2699</li>
                <li>Large size vehicle: R2999</li>
              </ul>
              <p class="text text-start">
                <strong>Duration:</strong> 240 minutes
              </p>
              <button
                class="btn btn-dark get-started-btn"
                @click="startBooking"
              >
                GET STARTED NOW
              </button>
            </div>
            <div class="col-md-8 px-4 text-start">
              <h4><strong>Optional extras:</strong></h4>
              <ul class="list-unstyled text-start">
                <li>Nasiol 1 year ceramic: R1500</li>
                <li>Nasiol 3 year ceramic coating: R2500</li>
                <li>Nasiol 5 year ceramic coating: R4500</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="platinum-package">
      <div class="container mt-5">
        <div class="package-container">
          <div class="package-header">
            <h2>Package 4</h2>
          </div>
          <div class="row">
            <div class="col-md-4">
              <h4><strong>Platinum</strong></h4>
              <img
                src="../assets/bmw-x7.jpg"
                alt="Car Image"
                class="package-image img-fluid rounded shadow"
              />
            </div>
            <div class="col-md-4">
              <h4><strong>All-Inclusive:</strong></h4>
              <div class="package-details">
                <ul class="list-circle">
                  <li>High level safe wash</li>
                  <li>High pressure rinse</li>
                  <li>Snow foam wash</li>
                  <li>High pressure rinse</li>
                  <li>Door jams, boot jams</li>
                  <li>Pedals cleaned</li>
                  <li>Air vents brushed clean</li>
                  <li>Plastics cleaned and UV protected</li>
                  <li>Deep clean brush out and vacuum</li>
                  <li>New car smell</li>
                  <li>Wheel arches cleaned and nourished</li>
                  <li>Door rubbers cleaned and nourished</li>
                </ul>
              </div>
            </div>
            <div class="col-md-4 mt-3 pt-3">
              <div class="package-details">
                <ul class="list-circle">
                  <li>Glass mirrors Crystal clear</li>
                  <li>Grills bumpers mirrors dried out</li>
                  <li>Bumpers, lips, defusers and tyres nourished</li>
                  <li>Exhaust tips cleaned and polished</li>
                  <li>Clay bar treatment</li>
                  <li>
                    Removes bonded contamination on the vehicle's windows and
                    paint surfaces
                  </li>
                  <li>
                    Stage 1 Paint correction 50% improvement on defected paint
                    Removes light swirls, holograms and blemishes
                  </li>
                  <li>
                    Stage 2 Glazing 50% improvement on defeced paint removes
                    light swirls, holograms and blemishes
                  </li>
                  <li>Spray coating 6 month protection</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="row mt-3 text-start">
            <div class="col-md-4 text-start package-pricing">
              <h4><strong>Pricing:</strong></h4>
              <ul class="list-unstyled text-start">
                <li>Small vehicle: R3499</li>
                <li>Medium size vehicle: R3899</li>
                <li>Large size vehicle: R4299</li>
              </ul>
              <p class="text text-start">
                <strong>Duration:</strong> 320 minutes
              </p>
              <button class="btn btn-dark get-started-btn">
                GET STARTED NOW
              </button>
            </div>
            <div class="col-md-8 px-4 text-start">
              <h4><strong>Optional extras:</strong></h4>
              <ul class="list-unstyled text-start">
                <li>Nasiol 1 year ceramic: R1500</li>
                <li>Nasiol 3 year ceramic coating: R2500</li>
                <li>Nasiol 5 year ceramic coating: R4500</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="platinum-plus-package mb-5">
      <div class="container mt-5">
        <div class="package-container">
          <div class="package-header">
            <h2>Package 5</h2>
          </div>
          <div class="row">
            <div class="col-md-4">
              <h4><strong>Platinum +</strong></h4>
              <img
                src="../assets/lamborghini-revuelto.jpg"
                alt="Car Image"
                class="package-image img-fluid rounded shadow"
              />
            </div>
            <div class="col-md-4">
              <h4><strong>All-Inclusive:</strong></h4>
              <div class="package-details">
                <ul class="list-circle">
                  <li>High level safe wash</li>
                  <li>High pressure rinse</li>
                  <li>Snow foam wash</li>
                  <li>High pressure rinse</li>
                  <li>Door jams, boot jams</li>
                  <li>Pedals cleaned</li>
                  <li>Air vents brushed clean</li>
                  <li>Plastics cleaned and UV protected</li>
                  <li>Deep clean brush out and vacuum</li>
                  <li>New car smell</li>
                  <li>Wheel arches cleaned and nourished</li>
                  <li>Door rubbers cleaned and nourished</li>
                </ul>
              </div>
            </div>
            <div class="col-md-4 mt-3 pt-3">
              <div class="package-details">
                <ul class="list-circle">
                  <li>Glass mirrors Crystal clear</li>
                  <li>Grills bumpers mirrors dried out</li>
                  <li>Bumpers, lips, defusers and tyres nourished</li>
                  <li>Exhaust tips cleaned and polished</li>
                  <li>
                    Undercarriage degrease and detail all plastics rubbers and
                    metals 60% improvement
                  </li>
                  <li>
                    Clay bar treatment: removes bonded contamination on the
                    vehicles windows and paint surfaces
                  </li>
                  <li>
                    Stage 1 paint correction: 50% improvement on defected paint
                    removes light swirls, holograms and blemishes
                  </li>
                  <li>
                    Stage 2 Glazing machine polish 30% provides a wet glossy
                    paint finish
                  </li>
                  <li>Spray coating 6 month protection</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="row mt-3 text-start">
            <div class="col-md-4 text-start package-pricing">
              <h4><strong>Pricing:</strong></h4>
              <ul class="list-unstyled text-start">
                <li>Small vehicle: R4499</li>
                <li>Medium size vehicle: R4899</li>
                <li>Large size vehicle: R5299</li>
              </ul>
              <p class="text text-start">
                <strong>Duration:</strong> 420 minutes
              </p>
              <button
                class="btn btn-dark get-started-btn"
                @click="startBooking"
              >
                GET STARTED NOW
              </button>
            </div>
            <div class="col-md-8 px-4 text-start">
              <h4><strong>Optional extras:</strong></h4>
              <ul class="list-unstyled text-start">
                <li>Nasiol 1 year ceramic: R1500</li>
                <li>Nasiol 3 year ceramic coating: R2500</li>
                <li>Nasiol 5 year ceramic coating: R4500</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="booking-form" v-if="showBookingForm">
    <div class="container mt-5 mb-5">
      <h2 class="mb-4 text-decoration-underline">Make a Booking</h2>
      <p class="text">You can book via email, phone or the form below</p>

      <div class="container d-flex flex-row flex-wrap justify-content-between text-light-emphasis">
        <div class="contact-item">
          <i class="fas fa-phone-alt"></i>
          <p>Phone (Joel): (062) 771 3590</p>
        </div>
        <div class="contact-item">
          <i class="fas fa-envelope"></i>
          <p>Email: info@jkwpdetailing.co.za</p>
        </div>
        <div class="contact-item">
          <i class="fas fa-calendar-alt"></i>
          <p>Mon-Sat: 8:00am - 5:00pm<br />Sun: 8:00am - 14:00pm</p>
        </div>
        <div class="contact-item">
          <i class="fas fa-map-marker-alt"></i>
          <p>
            Areas: We cover all the areas in Cape Town (Within 100km from the
            CBD)
          </p>
        </div>
      </div>
      <form
        action="https://formspree.io/f/xeojebvg"
        method="POST"
        enctype="multipart/form-data"
        @submit.prevent="handleSubmit"
      >
        <div class="row mb-3">
          <div class="col-md-6">
            <div class="form-floating">
              <input
                type="text"
                class="form-control"
                v-model="name"
                placeholder="Your Name"
                required
              />
              <label for="name">Full Name</label>
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-floating">
              <input
                type="email"
                class="form-control"
                v-model="email"
                placeholder="Your Email"
                required
              />
              <label for="email">Email address</label>
            </div>
          </div>
        </div>

        <div class="row mb-3">
          <div class="col-md-6">
            <div class="form-floating">
              <input
                type="tel"
                class="form-control"
                v-model="phone"
                placeholder="Your Phone Number"
                required
              />
              <label for="phone">Phone Number</label>
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-floating">
              <input
                type="date"
                class="form-control"
                id="appointment-date"
                v-model="appointmentDate"
                required
              />
              <label for="appointment-date">Preferred Date</label>
            </div>
          </div>
        </div>

        <div class="row mb-3">
          <div class="col-md-6">
            <div class="form-floating">
              <input
                type="time"
                class="form-control"
                id="appointment-time"
                v-model="appointmentTime"
                required
              />
              <label for="appointment-time">Preferred Time</label>
            </div>
          </div>
          <div class="col-md-6">
            <div class="form-floating">
              <select
                class="form-select"
                v-model="selectedPackage"
                id="package"
                required
              >
                <option value="" disabled>Select a package</option>
                <option value="bronze">Bronze Package</option>
                <option value="silver">Silver Package</option>
                <option value="gold">Gold Package</option>
                <option value="platinum">Platinum Package</option>
                <option value="platinum-plus">Platinum Plus Package</option>
              </select>
              <label for="package">Select Package</label>
            </div>
          </div>
          <div class="col-md-6 mt-3">
            <div class="form-floating">
              <select
                class="form-select"
                v-model="vehicleSize"
                id="vehicle-type"
                required
              >
                <option value="" disabled>Select vehicle size</option>
                <option value="Small">Small</option>
                <option value="Medium">Medium</option>
                <option value="Large">Large</option>
                <option value="Custom">Custom</option>
              </select>
              <label for="vehicle-type">Vehicle Size</label>
            </div>
          </div>
          <div v-if="vehicleSize === 'Custom'" class="col-md-6 mt-3">
            <div class="form-floating">
              <input
                type="text"
                class="form-control"
                v-model="customSize"
                id="custom-size"
                placeholder="Enter custom size"
              />
              <label for="custom-size">Custom Vehicle Size</label>
            </div>
          </div>
          <div class="col-md-6 mt-3">
            <div class="form-floating">
              <select
                class="form-select"
                v-model="detailedBefore"
                id="detailed-before"
                required
              >
                <option value="" disabled>Select an option</option>
                <option value="yes">Yes</option>
                <option value="no">No</option>
              </select>
              <label for="detailed-before"
                >Have you detailed this vehicle before?</label
              >
            </div>
          </div>
          <div class="col-md-6 mt-3">
            <div class="form-floating">
              <input
                type="text"
                class="form-control"
                v-model="vehicleColor"
                id="vehicleColor"
                placeholder="Vehicle Color"
                required
              />
              <label for="vehicleColor">Vehicle Color</label>
            </div>
          </div>
          <div class="col-md-6 mt-3">
            <div class="form-floating">
              <input
                type="text"
                class="form-control"
                v-model="vehicleName"
                id="vehicleName"
                placeholder="Vehicle Name/Model"
                required
              />
              <label for="vehicleName">Vehicle Name/Model</label>
            </div>
          </div>
        </div>

        <div class="row mb-3">
          <div class="col-md-6">
            <div class="form-floating">
              <input
                type="file"
                class="form-control"
                id="vehicle-images"
                @change="handleFileUpload"
                multiple
              />
              <label for="vehicle-images">Upload Images</label>
            </div>
          </div>
        </div>

        <div class="row mb-3">
          <div class="row mb-3">
            <div class="col-md-6">
              <div class="form-check text-start">
                <input
                  type="checkbox"
                  class="form-check-input"
                  v-model="bookingTerms"
                  id="bookingTerms"
                  required
                />
                <label class="form-check-label" for="bookingTerms">
                  I understand that booking is not instant and takes 1-2 days
                  for confirmation.
                </label>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-3 text-start">
          <button type="submit" class="btn btn-dark">Book Appointment</button>
        </div>
      </form>
    </div>
  </section>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    const name = ref("");
    const email = ref("");
    const phone = ref("");
    const appointmentDate = ref("");
    const appointmentTime = ref("");
    const selectedPackage = ref("");
    const vehicleSize = ref("");
    const customSize = ref("");
    const detailedBefore = ref("");
    const vehicleColor = ref("");
    const vehicleDirtyState = ref("");
    const vehicleName = ref("");
    const formTerms = ref(false);
    const bookingTerms = ref(false);
    const images = ref([]);
    const showBookingForm = ref(false);

    const handleFileUpload = (event) => {
      images.value = Array.from(event.target.files);
    };

    const handleSubmit = async (event) => {
      event.preventDefault();

      const formData = new FormData();
      formData.append("name", name.value);
      formData.append("email", email.value);
      formData.append("phone", phone.value);
      formData.append("appointmentDate", appointmentDate.value);
      formData.append("appointmentTime", appointmentTime.value);
      formData.append("selectedPackage", selectedPackage.value);
      formData.append("vehicleSize", vehicleSize.value);
      formData.append("customSize", customSize.value);
      formData.append("detailedBefore", detailedBefore.value);
      formData.append("vehicleColor", vehicleColor.value);
      formData.append("vehicleDirtyState", vehicleDirtyState.value);
      formData.append("vehicleName", vehicleName.value);
      formData.append("formTerms", formTerms.value);
      formData.append("bookingTerms", bookingTerms.value);

      images.value.forEach((file) => {
        formData.append("files[]", file);
      });

      try {
        const response = await fetch("https://formspree.io/f/xeojebvg", {
          method: "POST",
          body: formData,
        });

        if (response.ok) {
          alert("Your booking has been submitted successfully.");
          name.value = "";
          email.value = "";
          phone.value = "";
          appointmentDate.value = "";
          appointmentTime.value = "";
          selectedPackage.value = "";
          vehicleSize.value = "";
          customSize.value = "";
          detailedBefore.value = "";
          vehicleColor.value = "";
          vehicleDirtyState.value = "";
          vehicleName.value = "";
          formTerms.value = false;
          bookingTerms.value = false;
          images.value = [];
        } else {
          alert("There was a problem with your submission. Please try again.");
        }
      } catch (error) {
        alert("There was an error submitting the form. Please try again.");
      }
    };

    const startBooking = () => {
      showBookingForm.value = true;
    };

    return {
      name,
      email,
      phone,
      appointmentDate,
      appointmentTime,
      selectedPackage,
      vehicleSize,
      customSize,
      detailedBefore,
      vehicleColor,
      vehicleDirtyState,
      vehicleName,
      formTerms,
      bookingTerms,
      images,
      handleFileUpload,
      handleSubmit,
      showBookingForm,
      startBooking,
    };
  },
};
</script>
<style scoped>
.packages-heading {
  padding: 20px 10px;
}
.selection-options {
  padding: 10px 15px;
}
.button-option {
  padding: 5px 25px;
  display: inline-flex;
  margin: 15px;
}
.package-container {
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 20px;
  margin-top: 20px;
}
.package-header {
  text-align: center;
  margin-bottom: 20px;
}
.package-content ul {
  list-style-type: disc;
}
.package-content ul li {
  margin-left: 20px;
}
.package-pricing {
  text-align: right;
}
.list-circle {
  list-style-type: circle;
  text-align: left;
}
#custom-size-group {
  display: none;
}
.contact-info {
}
.contact-item {
  text-align: center;
}
.contact-item i {
  font-size: 24px;
  display: block;
  margin-bottom: 10px;
}
</style>
